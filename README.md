# dauphine-nonparametric_reg
## Situation

Nous disposons d'un jeu de données ![(X_{i},Y_{i})_{1\leq i\leq10^{4}}](https://render.githubusercontent.com/render/math?math=(X_%7Bi%2Cj%7D%2CY_%7Bi%2Cj%7D)_%7B1%5Cleq%20i%5Cleq10%5E%7B4%7D%7D) où les ![X_{i}](https://render.githubusercontent.com/render/math?math=X_%7Bi%7D) et ![Y_{i}](https://render.githubusercontent.com/render/math?math=X_%7Bi%7D) sont idéalisées comme des (réalisations de) variables aléatoires réelles admettant la représentation suivante :

![Y_{i} = r(X_{i}) + {\varepsilon }_i](https://render.githubusercontent.com/render/math?math=Y_%7Bi%7D%20%3D%20r(X_%7Bi%7D)%20%2B%20%7B%5Cvarepsilon%20%7D_i) pour ![i = 1,... ,10^{4}](https://render.githubusercontent.com/render/math?math=i%20%3D%201%2C...%2C10%5E%7Bi%7D) où les ![{\varepsilon }_i](https://render.githubusercontent.com/render/math?math=%7B%5Cvarepsilon%20%7D_i) sont indépendantes et identiquement distribuées, admettant une densité ![\mu](https://render.githubusercontent.com/render/math?math=%5Cmu) vérifiant ![\mathbb{E}\[{\varepsilon }_1\] = 0](https://render.githubusercontent.com/render/math?math=%5Cmathbb%7BE%7D%5B%7B%5Cvarepsilon%20%7D_1%5D%20%3D%200) et ![\mathbb{E}\[{{\varepsilon }_1}^2\] = {\sigma}^2 > 0](https://render.githubusercontent.com/render/math?math=%5Cmathbb%7BE%7D%5B%7B%7B%5Cvarepsilon%20%7D_1%7D%5E2%5D%20%3D%20%7B%5Csigma%7D%5E2%20%3E%200). 

Les ![X_{i}](https://render.githubusercontent.com/render/math?math=X_%7Bi%7D) sont indépendantes et identiquement distribuées de densité ![g : \[0,1\] \rightarrow \mathbb{R}](https://render.githubusercontent.com/render/math?math=g%20%3A%20%5B0%2C1%5D%20%5Crightarrow%20%5Cmathbb%7BR%7D), et indépendantes des ![{\varepsilon }_i](https://render.githubusercontent.com/render/math?math=%7B%5Cvarepsilon%20%7D_i).

La fonction ![r : \[0,1\] \rightarrow \mathbb{R}](https://render.githubusercontent.com/render/math?math=r%20%3A%20%5B0%2C1%5D%20%5Crightarrow%20%5Cmathbb%7BR%7D) vérifie ![\left | r(x) \right | \leq 6](https://render.githubusercontent.com/render/math?math=%5Cleft%20%7C%20r(x)%20%5Cright%20%7C%20%5Cleq%206) pour tout ![x\in \[0,1\]](https://render.githubusercontent.com/render/math?math=x%5Cin%20%5B0%2C1%5D).

## Objectifs

Les objectifs de cette étude sont :

- Reconstruire ![x \rightarrow g(x)](https://render.githubusercontent.com/render/math?math=x%20%5Crightarrow%20g(x)) graphiquement et étudier si ![g](https://render.githubusercontent.com/render/math?math=g) est la densité uniforme ou non.
- Reconstruire ![x \rightarrow r(x)](https://render.githubusercontent.com/render/math?math=x%20%5Crightarrow%20r(x)) graphiquement.
- Explorer les propriétés de ![x \rightarrow \mu(x)](https://render.githubusercontent.com/render/math?math=x%20%5Crightarrow%20%5Cmu(x)) et estimer ![\sigma ^ 2](https://render.githubusercontent.com/render/math?math=%5Csigma%20%5E%202).

