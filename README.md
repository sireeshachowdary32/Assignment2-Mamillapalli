# Assignment2-Mamillapalli
# Sireesha
###### Football
Food Ball is one of the most popular sport and its had large group of fan followers world wide.the best reason i like food ball because am big fan of **cristiano ronaldo**, Lionel Messi, Neymar their game style made me to watch regularly.especially am addicted to watch cristiano he scored 807 career goals, making him the highest ever **goalsscorer** in the history of the mens soccer.  

***
### Al-Nassr Fc

1. Talisca
2. David Ospina
3. Luit Gustavo

### other competitve teams

* Argentina National Football Team
* Australia National Football Team
* Belgium National Football Team

[aboutme](https://github.com/sireeshachowdary32/Assignment2-Mamillapalli/blob/main/AboutMe.md)

***
#### best Visiting Places

|**countries**| **discription**| **days to spend**  |
|   :---:   |     :---:   |     :---:     |
|  India  |  somany historical place  | 30  |
| Italy   |  best adventourous         |  5  |
|  Canada  |   niagara falls          |  3   |
|  Venice  |   beautiful bridges      |  10  |

***

> "you can't believe everything you hear-but you can repeat it"    *Mitch Hedburg*

> "there is nothing better than a friend, unless it's a friend with chocolate"  *Will Ferrel*

***
***WordPress***
[wordpress custom fields](https://css-tricks.com/snippets/wordpress/dump-all-custom-fields/)

```
<h3>All Post Meta</h3>

<?php 

  // Get all the data 
  $getPostCustom = get_post_custom(); 

    foreach($getPostCustom as $name=>$value) {

        echo "<strong>" . $name . "</strong>"."  =>  ";

        foreach ($value as $nameAr=>$valueAr) {
                echo "<br />";
                echo $nameAr."  =>  ";
                echo var_dump($valueAr);
        }

        echo "<br /><br />";

    }
?>
```
[wordpress stackoverflow](https://stackoverflow.com/questions/38469134/how-to-add-custom-fields-to-a-wordpress-plugin)