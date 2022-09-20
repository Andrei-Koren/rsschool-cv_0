## [rsschool-cv](#)
***

# Andrei Koran (Андрей Корень)

---

### [Contacts:](#)
  * Discord: Andrei_K#1122
  * E-mail: andrei-ko@tut.by
  * Tel: +375-29-1167597

***
***
#### _About myself:_
_I want to learn Front-End Development in RSSchool!_ 

***
### Skills
  + HTML5, CSS3
  + PHP
  + JavaScript (Basics)


---

###  Code:
 
        <?php 
        function Rus_word() {  //Create pseudo Russian words
            $char_x = array('а','б','в','г','д','е','ё','ж','з','и','й','к','л','м', 
            'н','о','п','р','с','т','у','ф','х','ц','ч','ш','щ','ъ','ы','ь','э','ю','я');
            $str='';
            $len=mt_rand(1, 12); //generate the length of the word
            for ($i=0; $i < $len; $i++){ 
                $x=mt_rand(0, 32);
                $str="$str"."$char_x[$x]";
                }
            return  $str;
            }
        ?>

---

#### Language:
- Russian
- Belorussian
- English with a dictionary *;)*