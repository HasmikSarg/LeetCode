# LeetCode Solutions em Java

Este repositório contém as minhas soluções para vários problemas do LeetCode, implementadas em Java. Cada problema está numa pasta separada, contendo o ficheiro da solução Java e o seu próprio README com a descrição do problema.

---

## ✅ Problemas Resolvidos

### 1. 53. Maximum Subarray  
**Dificuldade:** Média

Dado um array de inteiros `nums`, encontre o subarray com a maior soma e retorne a sua soma.

**Exemplo:**
```
Input: nums = [-2,1,-3,4,-1,2,1,-5,4]
Output: 6
Explanation: O subarray [4,-1,2,1] tem a maior soma 6.
```

---

### 2. 121. Best Time to Buy and Sell Stock  
**Dificuldade:** Fácil

Dado um array `prices` onde `prices[i]` é o preço de uma determinada ação no *i*-ésimo dia. Quer maximizar o seu lucro escolhendo um único dia para comprar uma ação e escolhendo um dia diferente no futuro para vender essa ação. Retorne o lucro máximo que pode obter com esta transação. Se não conseguir obter lucro, retorne 0.

**Exemplo:**
```
Input: prices = [7,1,5,3,6,4]
Output: 5
Explanation: Comprar no dia 2 (preço = 1) e vender no dia 5 (preço = 6), lucro = 6-1 = 5.
```

---

### 3. 152. Maximum Product Subarray  
**Dificuldade:** Média

Dado um array de inteiros `nums`, encontre um subarray que tenha o maior produto e retorne o produto. Os casos de teste são gerados de forma que a resposta caiba num inteiro de 32 bits.

**Exemplo:**
```
Input: nums = [2,3,-2,4]
Output: 6
Explanation: [2,3] tem o maior produto 6.
```

---

## 🛠️ Como Usar

Para compilar e executar qualquer uma das soluções Java:

### 1. Clone o repositório:
```bash
git clone <URL_DO_SEU_REPOSITORIO>
```

### 2. Navegue até a pasta do problema desejado:  
Exemplo:
```bash
cd LeetCode-0aa310c2618bc02fc1237c4e2020412914899540/0053-maximum-subarray
```

### 3. Compile o ficheiro Java:
```bash
javac Solution.java
```

### 4. Execute a solução (para testar, pode precisar de um método `main`):  
As soluções são geralmente projetadas para serem executadas diretamente na plataforma LeetCode. Para testar localmente, pode ser necessário adicionar um método `main` temporário à classe `Solution` para chamar o método principal com alguns casos de teste.

**Exemplo de `main` para Maximum Subarray:**

```java
public static void main(String[] args) {
    Solution sol = new Solution();
    int[] nums1 = {-2,1,-3,4,-1,2,1,-5,4};
    System.out.println("Max Subarray Sum for [-2,1,-3,4,-1,2,1,-5,4]: " + sol.maxSubArray(nums1)); // Expected: 6

    int[] nums2 = {1};
    System.out.println("Max Subarray Sum for [1]: " + sol.maxSubArray(nums2)); // Expected: 1
}
```

### 5. Depois de adicionar o `main`, compile e execute:
```bash
javac Solution.java
java Solution
```

---

## 📄 Licença

Este projeto está licenciado sob a Licença MIT. Consulte o ficheiro `LICENSE` para mais detalhes.

---

### MIT License

```
Copyright (c) 2025 Helena

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
