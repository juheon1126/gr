# gr
**C# 강의 6주차 과제**

# <강의 20화>

다음은 클래스 Player와 Enemy를 만들어 스테이터스를 지정한 예제입니다.
새로운 클래스를 만들고 각 클래스에서 겹치는 부분을 빼내어 상속시키는 형태로 변환하세요.
(강의 20화 11:00 ~ 15:00 참고)

```csharp
class Fightunit
{
    int AP = 100;
    int MP = 200;
    int HP = 10;
class Player : Fightunit
{
    int EXP = 0;
}
class Enemy : Fightunit
{

}

namespace _23inheritance
{
    internal class Program
    {
        private static void Main(string[] args)
        {

        }
    }
}
