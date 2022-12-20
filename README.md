# Buurtcampus-Oost

### De User-Story:

***

* _Als buurtbewoner van Amsterdam Oost wil ik een stekje kunnen toevoegen met behulp van een formulier_

Check hier mijn oplossing! https://rosahoffer.github.io/fix-the-flow-interactive-website/

![form-voorbeeld-readme-device-interactie-fixtheflow](https://user-images.githubusercontent.com/112861375/208641086-d92d03b6-5140-4b1b-85c1-2988b3eae789.png)

### Interactie

***

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

De pagina is gemaakt met HTML en CSS.


