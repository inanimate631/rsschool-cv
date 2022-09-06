# Name: 
Artem Suchevskii

## Contacts: 
gmaill: inanmate631@gmail.com, telegram: @qInan1mate

## Skills: 
JavaScript Basics, Git, GitHub, HTML5, CSS3, Figma

## Code example:

                            function slidesPlugin(activeSlide){
                            const slides = document.querySelectorAll('.slide')
                            slides[activeSlide].classList.add('active')
                        for (const slide of slides) {
                            slide.addEventListener('click', () =>{
                                clearActiveClasses()
                                slide.classList.add('active')
                            })
                        }                       
                        function clearActiveClasses(){
                            slides.forEach((slide) => {
                                slide.classList.remove('active')
                            })
                        }
                        }
                        slidesPlugin(0)

## Education: 
 Kiev State University of Telecommunications
 
 Faculty of Cybersecurity
 
## English: 
A2
