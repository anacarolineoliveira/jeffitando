 
using System ; 
using System.Collections.Generic ;
Using System.Linq ; 
Using System.Text ; 
Using System.Threading.Tasks 

namespace ; ConsoleApplication1

{

 Classe program
 {
    static void Main(string[] args)
    {//Início
        Console.BackgroundColor = ConsoleColor.Yellow;
        Console.Clear();
        Console.ForegroundColor = ConsoleColor.Black;
        double nota1, nota2, nota3, media;
        Console.WriteLine("Cálculo da Média do Aluno\n");
        Console.Write("Digite a 1ª nota: ");
        nota1 = Convert.ToDouble(Console.ReadLine());
        Console.Write("Digite a 2ª nota: ");
        nota2 = Convert.ToDouble(Console.ReadLine());
        Console.Write("Digite a 3ª nota: ");
        nota3 = Convert.ToDouble(Console.ReadLine());
        media = (nota1 + nota2 + nota3) / 3;
        Console.WriteLine("\nMédia: " + media);
        Console.WriteLine("\nPressione ENTER para Finalizar ...");
        Console.ReadKey();
      }//Fim
   }
}

