# what is this?

get meeting links of google meet according to your time slot and date.

provide your oath2 credentials and other arguments as input and you are ready to get the meeting links.

#installation

`npm i google-meet-api --save`

then ...

...

`const Meeting = require('google-meet-api').meet;`\

`Meeting({`\
    `clientId : 'XXXXdds420ghq7195tfsbi04i7rduaans.apps.googleusercontent.com',`\
    `clientSecret : 'XXXXxxeh2mrCZ',`\
    `refreshToken : 'XXXXXXXXXCNfW2MMGvJUSk4V7LplXAXXXX',`\
    `date : "2020-12-01",`\
    `time : "10:59",`\
    `summary : 'summary',`\
    `location : 'location',`\
    `description : 'description'`\
`}).then(function(result){`\
    `console.log(result);//result it the final link`\
`})`

## important

meet-api takes date and time input as the format shown above