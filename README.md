# -C-struct-.-129
//Структуры в C++ | struct   Разница между структурой и классом. #129
class Myclass
{
	
	int a = 10;
	void Print ()
	{ cout << a << endl; }

};
struct Mystruct
{
	~Mystruct()
	{
	}
	Mystruct()
	{
	}
	int a = 22;
	void Print ()
	{ cout << a << endl; }
};

int main()
{
	Myclass m;
	Mystruct ms;
	ms.a;
	ms.Print();
	return 0;
}
у Структуры - все поля по умолчанию public
у Класса - private
При наслед-ии, если не указываем модиф-р доступа, то у структуры-///struct Mystruct:struct Mystruct1
поля и методы класса наслед-ся как public по умолчанию
у Класса - private



