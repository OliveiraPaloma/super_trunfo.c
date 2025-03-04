# super_trunfo.c
Desafio super trunfo em C


    #include <stdio.h>

    int main (){

    char estado;
    char Código[50];
    char Nome_Cidade[50];
    int populacao, pontos_turisticos;
    float area, PIB;

    // Estrutura do projeto do Super Trunfo

    printf ("Inserir informações da primeira Carta:\n");

    printf("Digite o estado (letra de 'A' a 'H'):\n");
    scanf("%c", &estado);

    printf("Digite o cód da carta:\n");
    scanf("%s", &Código);

    printf("Digite o nome da cidade:\n");
    scanf("%s", &Nome_Cidade);

    printf("Digite a população:\n");
    scanf("%d", &populacao);

    printf("Digite a área em km²:\n");
    scanf("%f", &area);

    printf("Digite o PIB:\n");
    scanf("%f", &PIB);

    printf("Digite os pontos turisticos:\n");
    scanf("%d", &pontos_turisticos);

    //Exibir o que foi informado na primeira carta

    printf("Estado: %c\n", estado);
    printf("Código: %s\n", Código);
    printf("Nome da Cidade: %s\n", Nome_Cidade);
    printf("População: %d\n", populacao);
    printf("Área: %.2f km²\n", area);
    printf("PIB: R$ %.2f\n", PIB);
    printf("Pontos Turisticos: %d\n", pontos_turisticos);



    // Inserir dados da segunda carta

    printf ("Inserir informações da segunda Carta:\n");
    printf("Digite o estado (letra de 'A' a 'H'):\n");
    scanf("%c", &estado);

    printf("Digite o cód da carta:\n");
    scanf("%s", &Código);

    printf("Digite o nome da cidade:\n");
    scanf("%s", &Nome_Cidade);

    printf("Digite a população:\n");
    scanf("%d", &populacao);

    printf("Digite a área em km²:\n");
    scanf("%f", &area);

    printf("Digite o PIB:\n");
    scanf("%f", &PIB);

    printf("Digite os pontos turisticos:\n");
    scanf("%d", &pontos_turisticos);

    //Exibir o que foi informado na segunda carta
        
    printf("Estado: %c\n", estado);
    printf("Código: %s\n", Código);
    printf("Nome da Cidade: %s\n", Nome_Cidade);
    printf("População: %.d\n", populacao);
    printf("Área: %.2f km²\n", area);
    printf("PIB: R$ %.2f\n", PIB);
    printf("Pontos Turisticos: %d\n", pontos_turisticos);

    }
