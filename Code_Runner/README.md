# Instalando a extensão Code Runner no VS Code

Após instalar o compilador g++ do C++ e após instalar o VS Code, agora você pode instalar o plugin Code Runner.

O Code Runner permite que você execute um trecho de código ou um arquivo de código em várias linguagens de programação, incluindo códigos em linguagem C++.

Para instalá-lo, você pode pesquisar no marketplace do VS Code.

![](images/tela1.png)

Após a instalação, reinicie o VS Code.

Crie um arquivo com nome **test.cpp** e abra-o no VS Code. 
Digite o seguinte código C++ no arquivo e salve-o: 

```c++
#include <iostream>
using namespace std;
int main() 
{
    int x;
    cout << "Digite um inteiro: ";
    cin >> x;
    cout << "Dobro do inteiro digitado = " << x << endl;
    return 0;
}
```

## Executando seu código usando o Code Runner

- Use o atalho Ctrl+Alt+N.
- Ou pressione F1 e selecione/digite Run Code (Executar o código).
- Ou clique com o botão direito no editor de texto e clique em Run Code no menu de contexto do editor.

O código será executado e a saída será mostrada na janela de saída. Abra a janela de saída com o atalho Ctrl+.



