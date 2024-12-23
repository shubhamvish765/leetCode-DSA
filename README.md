# leetCode-DSA
# Lamada Function
 unordered_map<string, function<int(int,int)>>mp = {
            {"+",[](int a,int b){return a+b;}},
            {"-",[](int a,int b){return a-b;}},
            {"*",[](int a,int b){return a*b;}},
            {"/",[](int a,int b){return a/b;}}
        };

int result = mp[token](a,b);
st.push(result);
