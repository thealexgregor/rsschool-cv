# <center> Curriculum Vitae</center>

# <center> Aleksandr Grigoryan </center> 
#### <center>Web front-ent developer, beginner</center>

## Contacts

* Mobile number:
  + +37443120133,
* E-mail:
  + <thealexgregor@gmail.com>,
* LinkEdin:
  + [Link to profile,](https://www.linkedin.com/in/aleksandr-grigoryan-9670281aa/)

## About me...


 #### &nbsp;   I am married and have three wonderful children. The well-being of my family is of the highest priority for me. And programming for me is not a hobby, and not a tool for achieving financial well-being, but a means of realizing my creative ideas. When writing code, I feel free from pressing problems. I'm sure I will be a great programmer!


 ## Skills

* Front-end 
  + HTML, CSS, JS, ReactJS.
* Version Control:
  + git.


## Code example

    window.addEventListener('DOMContentLoaded', function () {

        'use strict';

        let tab = document.querySelectorAll('.info-header-tab'),
            info = document.querySelector('.info-header'),
            tabContent = document.querySelectorAll('.info-tabcontent');
        console.log(tabContent);

        function hideTabcontent(a) {
            for (let i = a; i < tabContent.length; ++i) {
                tabContent[i].classList.remove('show');
                tabContent[i].classList.add('hide');
            }
        }

        hideTabcontent(1);

        function showTabContent(b) {
            if (tabContent[b].classList.contains('hide')) {
                tabContent[b].classList.remove('hide');
                tabContent[b].classList.add('show');
            }
        }

        info.addEventListener('click', function (event) {
            let target = event.target;
            if (target && target.classList.contains('info-header-tab')) {
                for (let i = 0; tab.length; ++i) {
                    if (target == tab[i]) {
                        hideTabcontent(0);
                        showTabContent(i);
                        break;
                    }
                }
            }
        })
    });

## Еxperience (completed courses)

*  Microsoft innovation centre Armenia - Front-ent developer,
*  GITC Armenia - JS advanced
*  RS School - JS Pre-School

## Education

* SEUA High School, Master's degree

## English level

* А2

