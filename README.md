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

### Languages & Tools 
<p align='left'>
 <code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"></code>
 <code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/r/r.png"></code>
 <code><img height="40" src="https://cdn.vox-cdn.com/thumbor/E5DWi80rhjNBn1zQwrEjX0dnkLY=/0x0:640x427/920x613/filters:focal(0x0:640x427):format(webp)/cdn.vox-cdn.com/assets/1087137/java_logo_640.jpg"></code>
 <code><img height="40" src="https://raw.githubusercontent.com/github/explore/96943574ba0c0340ba6ea1e6f768e9abe43e34e1/topics/sql-server/sql-server.png"></code>
 <code><img height="40" src="https://avatars.githubusercontent.com/u/828667?s=200&v=4"></code>
 <code><img height="40" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png"></code>

 </p>

<span align="left"><img src="https://github-readme-stats.vercel.app/api/top-langs?username=michaelgru&bg_color=282923&title_color=A6E22E&text_color=66D9EF"></span>
