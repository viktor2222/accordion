# Accordion

```
let accordion = document.getElementsByClassName("accordion");

for (let i = 0; i < accordion.length; i++) {
  accordion[i].children[0].onclick = () => {
    let button = accordion[i].firstElementChild;
    let text = accordion[i].lastElementChild;
    text.classList.toggle("accordion-text-block"); // css class accordion-text-block
    button.classList.toggle("active-accordion"); //  css class active-accordion
  };
}

```
