# Ilya Kotov

___

#### Contacts:
* E-mail: martymartyrasyan@gmail.com
* Tel: +7 950 605-28-57
* GitHub: Komovvv

#### About Me:
I'm 19 years old, I study and sometimes work in the food industry. I decided to try something very new for me and interested in studying JS. That's why I chose this course.

#### Code example:
```
function onScroll(event){
    const curPos = window.scrollY;
    //console.log(curPos);
    let a1=0;
    document.querySelectorAll('body>.page-wrapper>#wrapper>a').forEach ((el)=>{
              
    
       if ( a1 <= curPos-150 && curPos-150 < (el.offsetTop+a1)) {
        
                MENU.querySelectorAll('a').forEach(a => {
              
                    a.classList.remove('active');
                if (a.getAttribute('href').substring(1)  === el.getAttribute('id')){            
                    a.classList.add('active');
                }
                });
          
       }

```
#### Work experience:
No work experience at the moment.

#### Languages:
* English(A1-A2)
* Russian
