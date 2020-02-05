# how to create a  Dynamic web pages with JavaScript 
### step1:create a new Repos
>go to github and click new and name your repos and gives it a desciription and initilaize it with readme.me
### step2:clone your project 
>you use the the command of git clone the of the url for example

` git clone https://github.com/alaaalmasri12/javascript-practice2.git`

### setp3:clone your other project by using the same command that you used in step2

### step4:write the command cp -r amman-102d2/class-06/starter-code/* practice-javascript/ 

### step5:

- create a folder put example in c01
- link the javascript to html file
- write the code of the javascript in your js file

`var today= new Date();`
`var hourNow = today.getHours(); var greeting;` 
`if (hourNow > 18) { greeting= 'Good evening!';` 
`else if (hourNow > 12) { greeting = ' Good afternoon!';`
`}`
`else if (hourNow > 0) { greeting = 'Good morning!';` 
`}`
`else {`
`greeting = 'Welcome! ' ;`
`}`

`document .write( ' <h3>' +greeting + ' </ h3>'); `
** result** : Good morni ng!
