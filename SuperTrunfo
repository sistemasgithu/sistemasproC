#include <stdio.h>

// Estrutura para a carta do Super Trunfo
struct Carta {
    char estado;
    char codigo[5];
    char cidade[50];
    int populacao;
    float area;                // km²
    float pib;                 // bilhões
    int pontosTuristicos;
    float densidadePop;        // habitantes por km²
    float pibPerCapita;        // reais
};

int main() {
    // Carta 1 - Fortaleza
    struct Carta carta1 = {
        'C',                     // Estado
        "C01",                   // Código
        "Fortaleza",             // Cidade
        2574412,                 // População
        312.353,                 // Área
        73.4,                    // PIB
        15,                      // Pontos turísticos
        7775.43,                 // Densidade Populacional
        27164.45                 // PIB per capita
    };

    // Carta 2 - Manaus
    struct Carta carta2 = {
        'A',                     // Estado
        "A02",                   // Código
        "Manaus",                // Cidade
        2303732,                 // População
        11401.0,                 // Área
        103.281,                 // PIB
        7,                       // Pontos turísticos
        181.01,                  // Densidade Populacional
        38881.0                  // PIB per capita
    };

    // Exibir Carta 1
    printf("\n--- Carta 1 ---\n");
    printf("Estado: %c\n", carta1.estado);
    printf("Codigo: %s\n", carta1.codigo);
    printf("Nome da Cidade: %s\n", carta1.cidade);
    printf("Populacao: %d habitantes\n", carta1.populacao);
    printf("Area: %.3f km2\n", carta1.area);
    printf("PIB: %.3f bilhoes de reais\n", carta1.pib);
    printf("Numero de Pontos Turisticos: %d\n", carta1.pontosTuristicos);
    printf("Densidade Populacional: %.2f hab/km2\n", carta1.densidadePop);
    printf("PIB per Capita: %.2f reais\n", carta1.pibPerCapita);

    // Exibir Carta 2
    printf("\n--- Carta 2 ---\n");
    printf("Estado: %c\n", carta2.estado);
    printf("Codigo: %s\n", carta2.codigo);
    printf("Nome da Cidade: %s\n", carta2.cidade);
    printf("Populacao: %d habitantes\n", carta2.populacao);
    printf("Area: %.3f km2\n", carta2.area);
    printf("PIB: %.3f bilhoes de reais\n", carta2.pib);
    printf("Numero de Pontos Turisticos: %d\n", carta2.pontosTuristicos);
    printf("Densidade Populacional: %.2f hab/km2\n", carta2.densidadePop);
    printf("PIB per Capita: %.2f reais\n", carta2.pibPerCapita);

    return 0;
}
