#include <stdio.h>
int main() {
    int n, i, is_prime = 1;
    scanf("%d", &n);
    if (n < 2) {
        printf("BUKAN\n");
        return 0;
    }
    for (i = 2; i <= sqrt(n); i++) {
        if (n % i == 0) {
            is_prime = 0;
            break;
        }
    }
    if (is_prime) {
        printf("PRIMA\n");
    } else {
        printf("BUKAN\n");
    }

    return 0;
}
