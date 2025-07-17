# backendPractice
- here i push some backend practice code for my understanding

## API data fetch using JQuery
```
  $.ajax({
          method: 'get',
          url:API_URL,
          success:(wheatherObj => {
            $('#lblCity').text(wheatherObj.name);
            $('#lblTemp').text(wheatherObj.main.temp);
          })
        })
```
<img src="https://github.com/Suprit202/backendPractice/blob/main/media/Screenshot%202025-07-10%20161350.png" width="60%" height="280px">

## Some Library To USe
```
  app.use(cors());
  app.use(express.urlencoded({extended:true}));
  app.use(express.json());
```
- Express requires CORS library to restrict the methods.
- CORS is Cross Origin Resource Sharing, that allows to enable or disable specific request method.
- Express requires a "body-parser" to convert the incoming data.
- Express latest versions are supported with a body-parser implicitly.

