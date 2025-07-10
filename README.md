# backendPractice
- here i push some backend practice code for my understanding

##API data fetch using JQuery
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
