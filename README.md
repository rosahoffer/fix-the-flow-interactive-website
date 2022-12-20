# Buurtcampus-Oost

### De User-Story:

***

* _Als buurtbewoner van Amsterdam Oost wil ik een stekje kunnen toevoegen met behulp van een formulier_

Check hier mijn oplossing! https://rosahoffer.github.io/fix-the-flow-interactive-website/

![test-form-voorbeeld-readme-device-interactie-fixtheflow](https://user-images.githubusercontent.com/112861375/208658002-8d6c4d48-592b-41f1-9217-1b7a1f5e21d5.png)


### Interactie

***

Voor het aanmelden van een stekje moest er een formulier komen. Dit heb ik door middel gedaan van een button waar hierna het formulier van beneden komt insliden. Dit heb ik gedaan met de volgende code in JS.

```js
// selecteer button open
let openButton = document.querySelector("#open-button-sign-in");

// selecteer pop up
let popUpForm = document.querySelector("#form-pop-up");

// selecteer button close
let closeButton = document.querySelector("#cancel-button")



// option 1
openButton.addEventListener('click', openForm);

function openForm(){
  popUpForm.showModal();
}

closeButton.addEventListener('click', closeForm);

function closeForm(){
  popUpForm.close();
}

```


### Kenmerken

***

De pagina is gemaakt met HTML, CSS en JS.


