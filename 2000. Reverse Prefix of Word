class Solution {
public:
    string reversePrefix(string w, char ch) {
        
        int ind = -1;
        for (int i = 0; i < w.size(); i++) {
            if (w[i] == ch) {
                ind = i;
                break;
            }
        }

        if (ind == -1) {
            return w;
        }

       reverse(w.begin(), w.begin() + ind + 1);

        return w;
    }
};
