-Grupo DeskTOPS
Enricco Rossi de Souza Carvalho Miranda RM: 551717
Erick Carvalho Pereira RM: 550772
Felipe de Vinicius Quinalha RM: 98957
Gabriel Marquez Trevisan RM: 99227
Silvia Hamazaki Kavabata RM: 97650



Back-end de aplicativo com sensor de nível de água de esgotos e rios


–DESCRIÇÃO
Este projeto recebe a leitura de um dispositivo Arduino que será colocado em esgotos e rios estratégicos, em locais de alagamento em São Paulo. Ele manda 3 níveis de água para o programa, onde 1 significa que o sensor foi ativado e 0 que não foi, ou seja, na soma de cada dispositivo, o "sensor a" não representa perigo de enchentes, o "sensor b" pede atenção e o "sensor c" mostra que ele está em sua capacidade máxima.
O programa pede para o usuário digitar o local que ele quer a informação sobre enchentes, e repete o pedido até que haja a entrada correta do dado. Depois, ele soma o valor dos sensores da região, e ,levando em consideração que colocamos como se fossem três sensores em cada local apenas para demonstração, se a soma for acima de 9, onde demonstraria que todos os sensores estão ativos, ele avisa que a área está alagada, caso seja 6, ou seja, dois sensores de cada bueiro, a área está em risco de alagamento, ou ele imprimi que não há risco algum.