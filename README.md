# supreme-spoon

Uma boa tarde para se criar um repositorio.

Primeira tentativa a criar um.

Os exemplos registrados aqui foram feitos nas aulas de Algoritmos

Esse é um algoritmo feito em codeblocks que testa se é possivel que um drone de entrega consegue passar pela janela com a entrega (Especificadamente, uma caixa).

Dentro deste sistema é avaliado 3 coisas, o tamanho da janela, o tamanho da caixa que o drone esta levando, e se é possivel o drone passar pela janela com a caixa


#include <iostream>

using namespace std;

int main()
{
    int a,b,c,h,l;
    
    1<=a,b,c<=100;
    
    1<=h,l<=100;
    
    cout<<"indique o tamanho da caixa : ";
    
    cin>>a;
    
    cin>>b;
    
    cin>>c;
    
    // indicada o tamanho da caixa
    
    cout<<"indique o tamanho da janela : ";
    
    cin>>h;
    
    cin>>l;
    
    //indicada o valor da janela
    
    if (a<=h&&b<=l){
    
    cout<<"S"<<endl;
    
    }else if(a<=l&&b<=h)
    
        cout<<"S"<<endl;
        
        else if(a<=h&&c<=l){
        
            cout<<"S"<<endl;
            
        }else if(a<=l&&c<=h){
        
            cout<<"S"<<endl;
            
            }else if(b<=l&&c<=h){
            
                cout<<"S"<<endl;
                
                }else if(b<=h&&c<=l){
                
                    cout<<"S"<<endl;
                    
                    }else(cout<<"N");
                    
//n essas sao as variaveis criadas para verificar se os valores de a,b,c conseguem passar pelos valores de h,l
//n se os valores de h,l forem maiores que os de a,b,c. a caixa passa e e digitado no sistema, se for o contrario, e digitado que nao passa
                }

