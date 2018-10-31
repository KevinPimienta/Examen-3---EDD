# Examen-3---EDD
Ejercicios
public void Ejercicio1()
        {
            Stack estak = new Stack();
            estak.Push("Fin");
            estak.Push(null);
            estak.Push(5);
            estak.Push(3);
            estak.Pop();
            estak.Push(2);
            estak.Push(8);
            estak.Pop();
            estak.Pop();
            estak.Push(9);
            estak.Push(1);
            estak.Pop();
            estak.Push(7);
            estak.Push(6);
            estak.Pop();
            estak.Pop();
            estak.Push(4);
            estak.Pop();
            estak.Pop();


            foreach (var itm in estak)
                Console.WriteLine(itm);
        }
