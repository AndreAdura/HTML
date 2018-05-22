# HTML
HTML Files for study

favicon generator:
https://www.favicon-generator.org/

validator:
https://validator.w3.org/#validate_by_input

formatter:
https://www.freeformatter.com/html-formatter.html#ad-output

bootstrap:
https://getbootstrap.com/docs/4.1/getting-started/introduction/
> Paste in the Head: <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" integrity="sha384-WskhaSGFgHYWDcbwN70/dfYBj47jz9qbsMId/iRN3ewGhXQFZCSftd1LZCfmhktB" crossorigin="anonymous">

Sublime - To install emmet - Open Sublime, Ctrl+Shift+p, install package, install package again, type emmet, click emmet;

Sublime tricks
- Ctrl + Space (show the auto-complete options for a command)
- <pre> </pre> (to preserve a "pre formated" text, with spaces and breaks)
- Ctrl + / (select all the content and input Ctrl + / to comment all)

Event Handler:

document.getElement.AddEventListener('action', function() { code } );
Ex:

showList.addEventListener('click', function() {

    OrderedList.removeAttribute('hidden');
    let employees = document.getElementsByClassName('employee');
    employees[0].innerHTML = 'Andre'
    employees[1].innerHTML = 'Milad'
    employees[2].innerHTML = 'Hibiki'
    employees[3].innerHTML = 'Satori'

});
