# level3-task9
int main() {
    int x;
    cout << "eded daxil edin=";
    cin >> x;
    int sum=0;
    for(int i=2;i<x;++i){
        if (x%i==0)
           sum=sum+1;
    }
    if (sum>0)
    cout << "sade eded deyil";
    else
    cout << "sade ededdir";
