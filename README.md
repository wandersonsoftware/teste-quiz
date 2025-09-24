# teste-quiz

package codigos;

import java.util.Scanner;

public class testequiz {
    public static void main(String[] args) {
        Scanner leia = new Scanner(System.in);

        cabecalho cabecalho0 = new cabecalho();
        System.out.println("----------------------------------------------------------------------------------------");

        cabecalho0.faculdade = "Faculdade: UNIFAN";
        cabecalho0.nome = "Nome: Wanderson Carvalho da Silva Junior";
        cabecalho0.materia = "Matéria: Algoritmo e Programação II";
        cabecalho0.professor = "Professor: Brenno Pimenta";
        cabecalho0.escrevaCabecalho();
        System.out.println("-----------------------------------------------------------------------------------------");


        int acertos = 0;

        questoes questoes1 = new questoes();

        questoes1.pergunta = "1) Quais são as duas sociedades consideradas clássicas?";
        questoes1.opcaoA = "A) Brasil e Argentina";
        questoes1.opcaoB = "B) Grécia e Roma";
        questoes1.opcaoC = "C) Inglaterra e França";
        questoes1.opcaoD = "D) Alemanha e Itália";
        questoes1.opcaoE = "E) Espanha e Portugal";
        questoes1.escrevaQuestoes();
        questoes1.correta = "b";
        System.out.println("Digite a resposta correta");
        String resposta = leia.nextLine();
        if (resposta.equals(questoes1.iscorreta(resposta))) {
        } else {
        }
        if (resposta.equals(questoes1.correta)){
            acertos = acertos + 1;
            System.out.println("Acertos:" + acertos);
        } else {
            System.out.println("Acertos:" + acertos);
        }
        System.out.println("-----------------------------------------------------------------------------------------");

        questoes questoes2 = new questoes();

        questoes2.pergunta = "2) Considerado o Maior líder francês?";
        questoes2.opcaoA = "A) Luis XIV";
        questoes2.opcaoB = "B) Carlos Magno";
        questoes2.opcaoC = "C) Napoleão Bonaparte";
        questoes2.opcaoD = "D) Kylian Mbappé";
        questoes2.opcaoE = "E) Joana D'Arc";
        questoes2.escrevaQuestoes();
        questoes2.correta = "c";
        System.out.println("Digite a resposta correta");
        String resposta2 = leia.nextLine();
        if (resposta.equals(questoes2.iscorreta(resposta2))) {
        } else {
        }
        if (resposta.equals(questoes2.correta)){
            acertos = acertos + 1;
            System.out.println("Acertos:" + acertos);
        } else {
            System.out.println("Acertos:" + acertos);
        }
        System.out.println("-----------------------------------------------------------------------------------------");


        questoes questoes3 = new questoes();

        questoes3.pergunta = "3) Qual a primeira capital do Brasil?";
        questoes3.opcaoA = "A) Rio de Janeiro";
        questoes3.opcaoB = "B) Palmas";
        questoes3.opcaoC = "C) Goiânia";
        questoes3.opcaoD = "D) São Paulo";
        questoes3.opcaoE = "E) Salvador";
        questoes3.escrevaQuestoes();
        questoes3.correta = "e";
        System.out.println("Digite a resposta correta");
        String resposta3 = leia.nextLine();
        if (resposta.equals(questoes3.iscorreta(resposta3))) {
        } else {
        }
        if (resposta.equals(questoes3.correta)){
            acertos = acertos + 1;
            System.out.println("Acertos:" + acertos);
        } else {
            System.out.println("Acertos:" + acertos);
        }
        System.out.println("-----------------------------------------------------------------------------------------");

        questoes questoes4 = new questoes();

        questoes4.pergunta = "4) Nome da primeira faraó egípcia?";
        questoes4.opcaoA = "A) Hatshepsut";
        questoes4.opcaoB = "B) Cleópatra";
        questoes4.opcaoC = "C) Nefertiti";
        questoes4.opcaoD = "D) Neitotepe";
        questoes4.opcaoE = "E) Meritaten";
        questoes4.escrevaQuestoes();
        questoes4.correta = "a";
        System.out.println("Digite a resposta correta");
        String resposta4 = leia.nextLine();
        if (resposta.equals(questoes4.iscorreta(resposta4))) {
        } else {
        }
        if (resposta.equals(questoes4.correta)){
            acertos = acertos + 1;
            System.out.println("Acertos:" + acertos);
        } else {
            System.out.println("Acertos:" + acertos);
        }
        System.out.println("-----------------------------------------------------------------------------------------");

        questoes questoes5 = new questoes();

        questoes5.pergunta = "5) Em qual ano marcou a chegada da família real portuguesa ao Brasil?";
        questoes5.opcaoA = "A) 1822";
        questoes5.opcaoB = "B) 1500";
        questoes5.opcaoC = "C) 1789";
        questoes5.opcaoD = "D) 1808";
        questoes5.opcaoE = "E) 1889";
        questoes5.escrevaQuestoes();
        questoes5.correta = "d";
        System.out.println("Digite a resposta correta");
        String resposta5 = leia.nextLine();
        if (resposta.equals(questoes5.iscorreta(resposta5))) {
        } else {
        }
        if (resposta.equals(questoes5.correta)){
            acertos = acertos + 1;
            System.out.println("Acertos:" + acertos);
        } else {
            System.out.println("Acertos:" + acertos);
        }
        System.out.println("-----------------------------------------------------------------------------------------");

        questoes questoes6 = new questoes();

        questoes6.pergunta = "6) Líder político que mais tempo no cargo máximo do país?";
        questoes6.opcaoA = "A) Getúlio Vargas";
        questoes6.opcaoB = "B) Dom Pedro II";
        questoes6.opcaoC = "C) Luís Inácio Lula da Silva";
        questoes6.opcaoD = "D) Juscelino Kubitschek";
        questoes6.opcaoE = "E) Fernando Henrique Cardoso";
        questoes6.escrevaQuestoes();
        questoes6.correta = "b";
        System.out.println("Digite a resposta correta");
        String resposta6 = leia.nextLine();
        if (resposta.equals(questoes6.iscorreta(resposta6))) {
        } else {
        }
        if (resposta.equals(questoes6.correta)){
            acertos = acertos + 1;
            System.out.println("Acertos:" + acertos);
        } else {
            System.out.println("Acertos:" + acertos);
        }
        System.out.println("-----------------------------------------------------------------------------------------");

        questoes questoes7 = new questoes();

        questoes7.pergunta = "7) Qual Guerra marcou o início da queda do segundo reinado?";
        questoes7.opcaoA = "A) Guerra da Independência";
        questoes7.opcaoB = "B) Guerra dos sete anos";
        questoes7.opcaoC = "C) Segunda Guerra Mundial";
        questoes7.opcaoD = "D) Revolta dos emboabas";
        questoes7.opcaoE = "E) Guerra do Paraguai";
        questoes7.escrevaQuestoes();
        questoes7.correta = "e";
        System.out.println("Digite a resposta correta");
        String resposta7 = leia.nextLine();
        if (resposta.equals(questoes7.iscorreta(resposta7))) {
        } else {
        }
        if (resposta.equals(questoes7.correta)){
            acertos = acertos + 1;
            System.out.println("Acertos:" + acertos);
        } else {
            System.out.println("Acertos:" + acertos);
        }
        System.out.println("-----------------------------------------------------------------------------------------");

        questoes questoes8 = new questoes();

        questoes8.pergunta = "8) Em que ano ocorreu a Restauração Meiji em que os samurais foram abolidos?";
        questoes8.opcaoA = "A) 1604";
        questoes8.opcaoB = "B) 1753";
        questoes8.opcaoC = "C) 1853";
        questoes8.opcaoD = "D) 1868";
        questoes8.opcaoE = "E) 1907";
        questoes8.escrevaQuestoes();
        questoes8.correta = "d";
        System.out.println("Digite a resposta correta");
        String resposta8 = leia.nextLine();
        if (resposta.equals(questoes8.iscorreta(resposta8))) {
        } else {
        }
        if (resposta.equals(questoes8.correta)){
            acertos = acertos + 1;
            System.out.println("Acertos:" + acertos);
        } else {
            System.out.println("Acertos:" + acertos);
        }
        System.out.println("-----------------------------------------------------------------------------------------");

        questoes questoes9 = new questoes();

        questoes9.pergunta = "9) Qual estado o Brasil comprou para anexar em seu território?";
        questoes9.opcaoA = "A) Rio de Janeiro";
        questoes9.opcaoB = "B) Mato Grosso";
        questoes9.opcaoC = "C) Acre";
        questoes9.opcaoD = "D) Rio Grande do Sul";
        questoes9.opcaoE = "E) Manaus";
        questoes9.escrevaQuestoes();
        questoes9.correta = "c";
        System.out.println("Digite a resposta correta");
        String resposta9 = leia.nextLine();
        if (resposta.equals(questoes9.iscorreta(resposta9))) {
        } else {
        }
        if (resposta.equals(questoes9.correta)){
            acertos = acertos + 1;
            System.out.println("Acertos:" + acertos);
        } else {
            System.out.println("Acertos:" + acertos);
        }
        System.out.println("-----------------------------------------------------------------------------------------");

        questoes questoes10 = new questoes();

        questoes10.pergunta = "10) Estados quais participavam ativamente da chamada República café co leite?";
        questoes10.opcaoA = "A) São Paulo e Minas Gerais";
        questoes10.opcaoB = "B) Rio de Janeiro e Bahia";
        questoes10.opcaoC = "C) Ceará e Pernambuco";
        questoes10.opcaoD = "D) Rio Grande do Sul e Santa Catarina";
        questoes10.opcaoE = "E) Mato Grosso e Goiás";
        questoes10.escrevaQuestoes();
        questoes10.correta = "a";
        System.out.println("Digite a resposta correta");
        String resposta10 = leia.nextLine();
        if (resposta.equals(questoes10.iscorreta(resposta10))) {
        } else {
        }
        if (resposta.equals(questoes10.correta)){
            acertos = acertos + 1;
            System.out.println("Acertos:" + acertos);
        } else {
            System.out.println("Acertos:" + acertos);
        }
        System.out.println("-----------------------------------------------------------------------------------------");

        questoes questoes11 = new questoes();

        questoes11.pergunta = "11) Acontecimento que marca a idade contemporânea?";
        questoes11.opcaoA = "A) Queda do Império Romano";
        questoes11.opcaoB = "B) Primeira Guerra Mundial";
        questoes11.opcaoC = "C) Revolução Industrial";
        questoes11.opcaoD = "D) Nascimento de Cristo";
        questoes11.opcaoE = "E) Revolução Francesa";
        questoes11.escrevaQuestoes();
        questoes11.correta = "e";
        System.out.println("Digite a resposta correta");
        String resposta11 = leia.nextLine();
        if (resposta.equals(questoes11.iscorreta(resposta11))) {
        } else {
        }
        if (resposta.equals(questoes11.correta)){
            acertos = acertos + 1;
            System.out.println("Acertos:" + acertos);
        } else {
            System.out.println("Acertos:" + acertos);
        }
        System.out.println("-----------------------------------------------------------------------------------------");

        questoes questoes12 = new questoes();

        questoes12.pergunta = "12) Qual país saiu da primeira guerra mundial devido a uma guerra interna?";
        questoes12.opcaoA = "A) Estados Unidos";
        questoes12.opcaoB = "B) União Soviética";
        questoes12.opcaoC = "C) Alemanha";
        questoes12.opcaoD = "D) Japão";
        questoes12.opcaoE = "E) México";
        questoes12.escrevaQuestoes();
        questoes12.correta = "b";
        System.out.println("Digite a resposta correta");
        String resposta12 = leia.nextLine();
        if (resposta.equals(questoes12.iscorreta(resposta12))) {
        } else {
        }
        if (resposta.equals(questoes12.correta)){
            acertos = acertos + 1;
            System.out.println("Acertos:" + acertos);
        } else {
            System.out.println("Acertos:" + acertos);
        }
        System.out.println("-----------------------------------------------------------------------------------------");

        questoes questoes13 = new questoes();

        questoes13.pergunta = "13) Último ditador da Ditadura Militar brasileira?";
        questoes13.opcaoA = "A) Figueiredo";
        questoes13.opcaoB = "B) Castelo Branco";
        questoes13.opcaoC = "C) Costa e Silva";
        questoes13.opcaoD = "D) Médici";
        questoes13.opcaoE = "E) Geisel";
        questoes13.escrevaQuestoes();
        questoes13.correta = "a";
        System.out.println("Digite a resposta correta");
        String resposta13 = leia.nextLine();
        if (resposta.equals(questoes13.iscorreta(resposta13))) {
        } else {
        }
        if (resposta.equals(questoes13.correta)){
            acertos = acertos + 1;
            System.out.println("Acertos:" + acertos);
        } else {
            System.out.println("Acertos:" + acertos);
        }
        System.out.println("-----------------------------------------------------------------------------------------");

        questoes questoes14 = new questoes();

        questoes14.pergunta = "14) Países que protagonizaram a Guerra Fria ?";
        questoes14.opcaoA = "A) Coreia do Norte e Coreia do Sul";
        questoes14.opcaoB = "B) China e Japão";
        questoes14.opcaoC = "C) União Soviética e Estados Unidos";
        questoes14.opcaoD = "D) Inglaterra e Alemanha";
        questoes14.opcaoE = "E) Vietnã e Estados Unidos";
        questoes14.escrevaQuestoes();
        questoes14.correta = "c";
        System.out.println("Digite a resposta correta");
        String resposta14 = leia.nextLine();
        if (resposta.equals(questoes14.iscorreta(resposta14))) {
        } else {
        }
        if (resposta.equals(questoes14.correta)){
            acertos = acertos + 1;
            System.out.println("Acertos:" + acertos);
        } else {
            System.out.println("Acertos:" + acertos);
        }
        System.out.println("-----------------------------------------------------------------------------------------");

        questoes questoes15 = new questoes();

        questoes15.pergunta = "15) Líder religioso que impulsionou na queda de Roma?";
        questoes15.opcaoA = "A) Maomé";
        questoes15.opcaoB = "B) Mahatma Gandhi";
        questoes15.opcaoC = "C) Salvador Dalí";
        questoes15.opcaoD = "D) Jesus Cristo";
        questoes15.opcaoE = "E) Buda";
        questoes15.escrevaQuestoes();
        questoes15.correta = "d";
        System.out.println("Digite a resposta correta");
        String resposta15 = leia.nextLine();
        if (resposta.equals(questoes15.iscorreta(resposta15))) {
        } else {
        }
        if (resposta.equals(questoes15.correta)){
            acertos = acertos + 1;
            System.out.println("Acertos:" + acertos);
        } else {
            System.out.println("Acertos:" + acertos);
        }
        System.out.println("-----------------------------------------------------------------------------------------");
    }
}
