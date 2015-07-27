# QualQuerTipoC-

   // Não dar para comparar um objeto com o outro e sim o atributo do objeto/;
            //
            Conta mauricio = new Conta();
            mauricio.numero = 1;
            mauricio.titular = "Mauricio";
            mauricio.saldo = 100.0;
            
            Console.WriteLine(mauricio.numero+ ""+ mauricio.saldo+ ""+ mauricio.titular);

            Conta mauricio2 = new Conta();
            mauricio2.numero = 1;
            mauricio2.titular = "Mauricio";
            mauricio2.saldo = 100.0;

            Console.WriteLine(mauricio2.numero + "" + mauricio2.saldo + "" + mauricio2.titular);

            if (mauricio == mauricio2)
            {
                MessageBox.Show("As contas são iguais");
            }
            else
            {
                MessageBox.Show("As contas são diferentes");
            }
