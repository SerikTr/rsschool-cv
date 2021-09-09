[rsschool-cv](https://rs.school/)
---
___
# Sergii Troian
---
## My contact Info:
* __Phone:__ ___+48 792 083 353___
* __E-mail:__ ___seriktr@gmail.com___
* __GitHub:__ ___https://github.com/SerikTr___
* __Linkedin:__ ___https://www.linkedin.com/in/sergii-troian-20639113a/___
___
## About Me:
I have extensive knowledge in front-end technologies. I am disciplined, conscientious,
focused on work and success. I am looking for an interesting job in which I can apply
 my own skills and gain new experience.
 ___
 ## Skills and Proficiency:
 * HTML, CSS/SASS, Bootstrap 4
 * JavaScript (ES6)
 * Angular 9
 * Typescript - RxJS, AJAX 
* RESTful API, HTTP
 * GIT
 ---
 ## Code example:
 The purpose of the task was to find a match of the channel names from the resulting JSON file using a search string. And display it on the page.
 * [Project: JS Channels.](https://channel-list-87d07.web.app/)
 * [More code on GitHub...](https://github.com/SerikTr/recruitment-task/blob/main/static/js/search.js)
 >  function searchChannel() {
    searchBar.addEventListener('input', (e) => {
      const searchString = e.target.value.toUpperCase().trim()
      const channelsContainer = document.querySelector('.wrapper__content')
      const channels = channelsContainer.getElementsByClassName('inner__content')
      const channelList = document.getElementById('channelList')
      const array = []
      for (let i = 0; i < channels.length; i++) {
        let title = channels[i].querySelector('.title__content')
        if (title.innerText.toUpperCase().indexOf(searchString) > -1) {
          channels[i].style.display = ""
          let str = title.innerText
          title.innerHTML = insertMark(str, title.innerText.toUpperCase().indexOf(searchString), searchString.length)
          if (searchString.length > 0) {
            array.push(title.innerText)
          }
        } else {
          channels[i].style.display = "none"
        }
      }
      let html = array.map(title =>
        `<option>${title}</option>`
      ).join('')
      channelList.innerHTML = html
    })
  }
  ___
## Education:
Higher Professional Technical College # 27 of the city of Zaporizhia  08/2003 - 06/2006
___

  ## Courses:
  * Javascript full course. (Udemy Ivan Pietriczenko).
  * Angular for beginners (Udemy Vladilen Minin).
___
