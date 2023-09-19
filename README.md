# 18
#include <iostream>

using namespace std;

int main() {
    int m,n;
    cout<<"输入两个整数：";
    cin >>m >> n;
    cout<<m <<endl;
    cout<<n<<endl;
    int r = m%n;
    while(r!=0){
        m=n;
        n=r;
        r=m % n;
    }
    cout <<"HCF="<< n << endl;
    return 0;
}
