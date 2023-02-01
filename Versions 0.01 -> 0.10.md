#Most of these require JQUERY use this as an injector for JQUERY:
javascript:void(function(){document.body.appendChild(document.createElement('script')).src='https://code.jquery.com/jquery-3.6.0.js' })();


#Version 0.01 :
javascript:(function()%7Bfunction%20callback()%7B(function(%24)%7Bvar%20jQuery%3D%24%3BtitlePage%20%3D%20'Google'%3Bdocument.title%20%3D%20titlePage%3Bdocument.querySelector(%22link%5Brel*%3D'icon'%5D%22).href%20%3D%20%22https%3A%2F%2Ficons.iconarchive.com%2Ficons%2Fpapirus-team%2Fpapirus-apps%2F256%2Fgoogle-icon.png%22%7D)(jQuery.noConflict(true))%7Dvar%20s%3Ddocument.createElement(%22script%22)%3Bs.src%3D%22https%3A%2F%2Fajax.googleapis.com%2Fajax%2Flibs%2Fjquery%2F1.11.1%2Fjquery.min.js%22%3Bif(s.addEventListener)%7Bs.addEventListener(%22load%22%2Ccallback%2Cfalse)%7Delse%20if(s.readyState)%7Bs.onreadystatechange%3Dcallback%7Ddocument.body.appendChild(s)%3B%7D)()

#Version 0.02:
javascript:(function()%7BtitlePage%20%3D%20'Google'%3Bdocument.title%20%3D%20titlePage%3Bdocument.querySelector(%22link%5Brel*%3D'icon'%5D%22).href%20%3D%20%22https%3A%2F%2Ficons.iconarchive.com%2Ficons%2Fpapirus-team%2Fpapirus-apps%2F256%2Fgoogle-icon.png%22%3Bvar%20menuStyles%20%3D%20%7Bcolor%3A%20%22%23e6eaf5%22%2CbackgroundColor%3A%20%22%232b2c2e%22%2Cheight%3A%20%22200px%22%2Cwidth%3A%20%22200px%22%2C%7D%3Blet%20menu%20%3D%20document.createElement('div')%3Bfor%20(let%20style%20in%20menuStyles)%20%7Bmenu.style%5Bstyle%5D%20%3D%20menuStyles%5Bstyle%5D%3B%7Dbody.appendChild(menu)%7D)()
