<details>
<summary>"Click to expand"</summary>
  
>consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</details>
<p align="left"><img src="https://raw.githubusercontent.com/michaelGRU/michaelGRU/main/gapminder.gif"></p>

<details>
<summary>"Click to expand"</summary>

```r
library(gapminder)
library(gganimate)
library(ggplot2)
## standard ggplot2
ggplot(gapminder, aes(gdpPercap, lifeExp, size = pop, colour = country)) +
  geom_point(alpha = 0.7, show.legend = FALSE) +
  scale_colour_manual(values = country_colors) +
  scale_size(range = c(2, 12)) +
  scale_x_log10() +
  # Here comes the gganimate specific bits
  labs(title = 'Year: {frame_time}', x = 'GDP per capita', y = 'life expectancy') +
  transition_time(year) +
  ease_aes('linear')

```

</details>

### Languages 
<p align='left'>
  <code><img height="60" width="60" src="https://raw.githubusercontent.com/recklessn00b/recklessn00b/main/java.PNG"></code>
 <code><img height="60" width="60" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"></code>
 <code><img height="60" width="60" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/r/r.png"></code>
   <code><img height="60" width="60" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/matlab/matlab.png"></code>
 
 <code><img height="60" width="60" src="https://camo.githubusercontent.com/921feef2c4a66db28e70f982bbfea8f22e6e75f1d3818b1af8cca5cd62c361ff/68747470733a2f2f7777772e7a656c75736c7567692e72752f75706c6f61642f6e6577732f7465726d7332303139313131352d312e706e67"></code>
  <code><img height="60" width="60" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
 <code><img height="60" width="60" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"></code>
 <code><img height="60" width="60" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/bash/bash.png"></code>

 </p>
<p align="left"><img src="https://github-readme-stats.vercel.app/api/top-langs?username=michaelgru&bg_color=282923&title_color=A6E22E&text_color=66D9EF&langs_count=8"></p>

