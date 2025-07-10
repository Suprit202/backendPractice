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
<img src="https://github.com/Suprit202/backendPractice/blob/main/media/Screenshot%202025-07-10%20161350.png" width="100%" height="100%">
