int lonelyinteger(vector<int> a) {
int unique=0;
for(int i:a){
    unique ^=i;
}
return unique;
}
