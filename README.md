#include <stdio.h>

void movTorre(int movT) {
    for (int i = 0; i < movT; i++) {
        printf("Torre: Direita\n\n");
    }
}

void movBispo(int movB) {
    for (int i = 0; i < movB; i++) {
        printf("Bispo: Cima\n\n");
    }
    for (int i = 0; i < movB; i++) {
        printf("Bispo: Direita\n\n");
    }
}

void movRainha(int movR) {
    for (int i = 0; i < movR; i++) {
        printf("Rainha: Esquerda\n\n");
    }
}

void movCavalo(int cimaC, int direitaC) {
    for (int i = 0; i < cimaC; i++) {
        printf("Cavalo: Cima\n\n");
    }
    for (int i = 0; i < direitaC; i++) {
        printf("Cavalo: Direita\n\n");
    }
}

int main() {
    movTorre(5);
    movBispo(5);
    movRainha(8);
    movCavalo(2, 1);
    return 0;
}
