using System;

namespace DannyPractice
{
    class Program
    {
        static void Main(string[] args)
        {
            Random random = new Random();
            bool playAgain = true;
            String player;
            String computer;
            string answer;        

            while (playAgain)
            {
                player = "";
                computer = "";

                while (player != "ROCK" && player != "PAPER" && player != "SCISSORS")
                {
                    Console.Write("Enter, Rock, Paper or Scissors: ");
                    player = Console.ReadLine();
                    player = player.ToUpper();
                }

                switch (random.Next(1, 4))
                {
                    case 1:
                        computer = "ROCK";
                        break;
                    case 2:
                        computer = "PAPER";
                        break;
                    case 3:
                        computer = "SCISSORS";
                        break;
                }

                Console.WriteLine("Player: " + player);
                Console.WriteLine("Computer: " + computer);

                switch (player)
                {
                    case "ROCK":
                        if (computer == "ROCK")
                        {
                            Console.WriteLine("IT'S A DRAWWWWWWWW");
                        }
                        else if (computer == "PAPER")
                        {
                            Console.WriteLine("You loseeee");
                        }
                        else
                        {
                            Console.WriteLine("YOU WINNNN!");
                        }
                        break;
                    case "PAPER":
                        if (computer == "ROCK")
                        {
                            Console.WriteLine("You Win");
                        }
                        else if (computer == "SCISSORS")
                        {
                            Console.WriteLine("You LOSE");
                        }
                        else
                        {
                            Console.WriteLine("IT'S A DRAWWWW");
                        }
                        break;
                    case "SCISSORS":
                        if (computer == "SCISSORS")
                        {
                            Console.WriteLine("IT'S A DRAWWW");
                        }
                        else if (computer == "ROCK")
                        {
                            Console.WriteLine("YOU LOSE");
                        }
                        else
                        {
                            Console.WriteLine("YOU WIN");
                        }
                        break;
                }

                Console.WriteLine("Would you like to play again (Y/N): ");
                answer = Console.ReadLine();
                answer = answer.ToUpper();

                if (answer == "Y")
                {
                    playAgain = true;
                }
                else
                {
                    playAgain = false;
                }
            }


            Console.WriteLine("STHANK YOU VWERY MUSH!");
            Console.ReadKey();
        }
    }
}
