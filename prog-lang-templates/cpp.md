# C++ competitive programming header

```cpp
//house keeping stuuf
#include <bits/stdc++.h>
#define DEBUG false
#define OJ_DEBUG

#define $(x) {if (DEBUG) {cout << __LINE__ << ": "; {x} cout << endl;}}
#define _(x) {cout << #x << " = " << x << " ";}
#define For(i, n)for( int i = 0;i<n;i++)
#define FOR(i,f,t)for( int i = f;i<t;i++)
#define RFor(i,f)for(int i = f;i>=0;i--)
#define RFOR(i,f,t)for(ll i = f;i>=t;i--)
#define Iter(i,a) for(decltype(a.begin()) i = a.begin();i != a.end();i++)
#define range(c) c.begin(), c.end()
#define ff first
#define ss second
#define pf printf
#define ins insert
#define pb push_back
#define sz size
#define gcd __gcd
#define PI 3.1415926535897932384626433832795

//using fucking everything
using namespace std;

//more shortcuts
typedef long long ll;
typedef pair<int, int> pii;
typedef pair<double ,double> pdd;
typedef pair<ll, ll> pll;
//one long shortcut 
typedef unsigned long long ull;

//too much performance
inline void magic_optimalization(){ios_base::sync_with_stdio(false);cin.tie(0);cout.tie(0);}
template <class T, class U> ostream& operator<<(ostream& out, pair<T,U>& v) { return out << "{" <<v.first << "," << v.second << "}"; }
template <class T> ostream& operator<<(ostream& out, vector<T> &v){out<<"[";for(int i=0;i<v.size();i++)out<<v[i]<<(i==v.size()-1?"":","); out << "]"; return out;}
inline ll toInt(string s){stringstream ss(s);ll a; ss >> a;return a;}
inline string toStr(ll s){stringstream ss;ss << s; return ss.str();}
inline ll mod(ll n,ll m){ return ((n % m)+m)%m;}
```