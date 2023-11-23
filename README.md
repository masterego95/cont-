# cont-
estudo np2
linguagem C
#include <stdio.h>

int main() {
    int cont, soma = 0, notas, media;

    for (cont = 1; cont <= 10; cont++) {
        printf("Digite a %da nota: ", cont);
        scanf("%d", &notas);
        soma += notas;
    }

    media = soma / 10;

    printf("O total das notas foi %d e a média foi %d\n", soma, media);

    return 0;
}


laço do-while
#include <stdio.h>

main() {
    int cont = 1, soma = 0, notas, media;

    do {
        printf("Digite a %dª nota: ", cont);
        scanf("%d", &notas);
        soma += notas;
        cont++;
    } while (cont <= 10);

    media = soma / 10;

    printf("O total das notas foi %d e a média foi %d\n", soma, media);

    return 0;
}
