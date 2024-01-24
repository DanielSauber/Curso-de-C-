# Curso-de-C-
Exercicios do curso de C# Introducao


using System;

class Program
{
    static void Main()
    {
      Console.WriteLine("Linha digitada com quebra\nEste trecho será escrito na linha abaixo"); // usamos \n;
      Console.WriteLine("Esta linha será escrita ao lado\t- percebe?");
      Console.WriteLine("O Caminho do arquivo é: C:\\USERS\\DOCUMENTS\\REGISTER"); // Usamos a "\\" para não confundir o compilador, o mesmo tem por regra a barra como reserva
      Console.WriteLine("Para escrever entre \"\" duplas usamos \\");//para escrever entre aspas duplas, colocamos contra barra entre o que se quer escrever.
  
      Console.WriteLine("Olá\nMundo!");
      Console.WriteLine("Olá\tMundo!");

       Console.WriteLine("Gerando Invoice para consumidor \"ABC Corp\" ...\n");
       Console.WriteLine("Invoice: 1021\t\tCompleta!");
       Console.WriteLine("Invoice: 1022\t\tCompleta!");
       Console.WriteLine("\nDiretório de saída:\t");
       Console.WriteLine(@"C:\Users\Downloads");

      //Instruções em Japonês
      //podemos usar a codificação UTF que, neste caso,  "traduz" para japonês (UTF-16)

    Console.WriteLine("\u3053\u3093\u3061\u306F Mundo!");
      //Gerando Invoice em Japones

      Console.WriteLine("Gerando Invoice para consumidor \"ABC Corp\" ...\n");
       Console.WriteLine("Invoice: 1021\t\tCompleta!");
       Console.WriteLine("Invoice: 1022\t\tCompleta!");
       Console.WriteLine("\nDiretório de saída:\t");
       // para gerar invoice em japonês - Nihon seikyu-sho o seisei suru ni wa 
      Console.WriteLine("\n\n\u65e5\u672c\u306e\u8acb\u6c42\u66f8\u3092\u751f\u6210\u3059\u308b\u306f\uff1a\n\t");
      Console.WriteLine(@"C:\invoices\app.exe");
    }
}
