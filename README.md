 LEARNED IN THIS LESSON:


--------------------
for of

example: 

function getEmotionsArray(cats){
    for (let cat of cats){
        console.log(cat)
    }
--------------------


--------------------
import/export

example:

1. create new file
2. addition of type=“module”
example: <script src="index.js" type="module"></script>
3. add “export” to all const & functions (etc) in new file
4. add “import { thing to import } from ‘/filepath.js” in main .js file
--------------------


--------------------
<input> types radio and checkbox
--------------------


--------------------
querySelector

example:

document.querySelector(‘input[type=“radio"]:checked')
this example will take control of all radio inputs that are checked
--------------------


--------------------
getElementsByClassName & classList.remove

example:

const radios =  document.getElementsByClassName(‘class/classname’)
	for (let class of classes) {
		class.classList.remove(‘class/classname’)
	}
--------------------


--------------------
.includes()

example: 

if (item.includes(“example”){
	return item
	})
--------------------


--------------------
.filter()

example:

[##, ##, ##, #, #, ##]   <—(an array with numbers

const adult = ages.filter(age){
	return age >= 18
})
--------------------