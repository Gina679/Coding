1. fsolve vs vpasolve
- fsolve 是双精度，vpa是变精度，一般来说，vpasolve更准确。
- 但是遇到一个问题，gamma函数可以允许symbolic expression但是gammainc不可以，但后来发现有一个igamma可以解决这个问题
