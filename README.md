# Hello 👋, I'm Kyle

### Software Engineer // Developer // Nerd

![github follow](https://img.shields.io/github/followers/kylereddoch?label=Followers&logo=github)
[![twitter follow](https://img.shields.io/twitter/follow/winphankyle?label=Follow&logo=twitter&style=flat)](hhttps://twitter.com/intent/follow?screen_name=winphankyle)
![visitors](https://visitor-badge.glitch.me/badge?page_id=kylereddoch.kylereddoch&left_color=black&right_color=blue)

### A little about me... 😎

```swift
import CaffeineKit
import NerdKit
import SwiftUI

struct Kyle: View {
    let currentActivity = "Building the next big thing"
    let currentLocation = "Amarillo, TX"
    let askMeAbout: [Questions] = [programming, apple tech, shortcuts]
    let languages: [Languages] = [php, python, java, swift, javascript, html, css]
    let tools: [Software] = [VS Code, xCode, Git]
    let interests: [Interests] = [programming, apple tech, family, music]
    var favoriteDrink: String {
        let calendar = Calendar.current
        let hour = calendar.component(.hour, from: .now)
        if hour < 12 {
            return "Coffee"
        } else if hour < 18 {
            return "Dr Pepper, Tea, or Water"
        } else {
            return "Tea or Water"
        }
    }

    var body: some View {
        VStack {
            Text("Hello, I'm Kyle")
            Text("I'm currently \(currentActivity) in \(currentLocation)")
            Text("Some programming lanuages I know are: \(languages)")
            Text("Tools that I use regularly: \(tools)")
            Text("I'm interested in: \(interests)")
            Text("You can ask me about: \(askMeAbout)")
            Text("My favorite drink is \(favoriteDrink)")
        }
    }
}
```

### Let's meet and chat!

![Schedule a meeting with me!](images/schedule_meeting.png)

👇 Type the following in your console or terminal to connect with me.

```bash
npx kylereddoch
```

**👆 This command line tool can be [found here](https://github.com/kylereddoch/npx_card). <!-- If you are interested in learning how to make your own command line tool, check out my [article here]().-->**

### Where you can find me

- [My website][website]
- <a rel="me" href="https://iosdev.space/@kylewritescode">Mastodon</a>
- [Twitter][twitter]
- [Instagram][instagram]

### Check out what I am currently up to 👇🏼

[Here's what I'm up to][now].

---

### 📝 Latest Blog Posts

<!-- BLOG-POST-LIST:START -->
- [Tutorial: Create a Simple npx Business Card](https://kylereddoch.me/2022/09/26/create-a-simple-npx-business-card.html)
- [Tutorial: Pseudocode and Flowcharts for Coding](https://kylereddoch.me/2022/03/19/pseudocode-and-flowcharts.html)
- [Review: Forte - The Better Habit Tracker](https://kylereddoch.me/2022/01/24/review-forte-habit-tracker.html)
- [Review: Working Copy, A Git Client for iPhone and iPad](https://kylereddoch.me/2021/12/23/review-working-copy-git-client.html)
- [WakaStats - A Scriptable Script for Your WakaTime Data](https://kylereddoch.me/2021/12/12/wakastats-scriptable-script.html)
<!-- BLOG-POST-LIST:END -->

➡️ [more blog posts...](https://kylereddoch.me)

---

### 📊 GitHub Stats

<p><img src="https://github-readme-stats-sigma-rouge.vercel.app/api?username=kylereddoch&show_icons=true&hide_border=true&locale=en" alt="kylereddoch" /></p>
<p><img src="https://github-readme-stats-sigma-rouge.vercel.app/api/top-langs?username=kylereddoch&show_icons=true&hide_border=true&locale=en&layout=compact" alt="kylereddoch" /></p>

---

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-148%20hrs%2052%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-10-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-17%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 223 Contributions in the Year 2022
 > 
> 📦 75.8 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 22 Public Repositories 
 > 
> 🔑 2 Private Repositories  
 > 
**I'm a Night 🦉** 

```text
🌞 Morning    30 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.23% 
🌆 Daytime    109 commits    ████████░░░░░░░░░░░░░░░░░   33.54% 
🌃 Evening    151 commits    ███████████░░░░░░░░░░░░░░   46.46% 
🌙 Night      35 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.77%

```
📅 **I'm Most Productive on Saturday** 

```text
Monday       29 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.92% 
Tuesday      38 commits     ███░░░░░░░░░░░░░░░░░░░░░░   11.69% 
Wednesday    51 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.69% 
Thursday     15 commits     █░░░░░░░░░░░░░░░░░░░░░░░░   4.62% 
Friday       47 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.46% 
Saturday     84 commits     ██████░░░░░░░░░░░░░░░░░░░   25.85% 
Sunday       61 commits     ████░░░░░░░░░░░░░░░░░░░░░   18.77%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: America/Chicago

💬 Programming Languages: 
SCSS                     46 mins             ██████████░░░░░░░░░░░░░░░   41.03% 
YAML                     17 mins             ████░░░░░░░░░░░░░░░░░░░░░   15.83% 
Ruby                     15 mins             ███░░░░░░░░░░░░░░░░░░░░░░   13.99% 
Other                    12 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   11.39% 
HTML                     10 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   9.16%

🔥 Editors: 
VS Code                  1 hr 53 mins        █████████████████████████   100.0%

🐱‍💻 Projects: 
kylereddoch.github.io    1 hr 53 mins        █████████████████████████   100.0%

💻 Operating System: 
Mac                      1 hr 53 mins        █████████████████████████   100.0%

```

**I Mostly Code in C++** 

```text
C++                      6 repos             ████████░░░░░░░░░░░░░░░░░   35.29% 
Python                   4 repos             ██████░░░░░░░░░░░░░░░░░░░   23.53% 
Swift                    2 repos             ███░░░░░░░░░░░░░░░░░░░░░░   11.76% 
JavaScript               2 repos             ███░░░░░░░░░░░░░░░░░░░░░░   11.76% 
Shell                    1 repo              █░░░░░░░░░░░░░░░░░░░░░░░░   5.88%

```



<!--END_SECTION:waka-->

---

### 🙏🏼 Support

I love being able to offer people the tools/software that help make a difference in their lives. Your support helps continue to make that happen. There is no pressure, though. If you like what I am doing and use what I put out, please consider supporting me through the various options below. I have set up both one-time donations and membership tiers. (Those that support me through memberships get extra perks!)

- [Sponsor me on GitHub :heart:][githubsponsor]
- [Nominate me to GitHub Stars :star2:][githubstars]

<a href="https://www.buymeacoffee.com/kylereddoch" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

<a href='https://ko-fi.com/S6S374TCV' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://cdn.ko-fi.com/cdn/kofi1.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

_NOTE: Top languages does not indicate my skill level or anything like that. It is just a metric of which languages have been hosted by me on GitHub based on the usage across repositories. There are others that have not been put on Github._

[website]: https://kylereddoch.me
[twitter]: https://twitter.com/winphankyle
[instagram]: https://instagram.com/kyle.reddoch
[linkedin]: https://linkedin.com/in/kylereddoch
[wakatime]: https://wakatime.com/@10619014-9413-4a5b-a3df-2d3892b8a73d
[telegram]: https://t.me/kylereddoch
[email]: kylereddoch@me.com
[hwscourses]: https://www.hackingwithswift.com
[githubstars]: https://stars.github.com/nominate/
[githubsponsor]: https://github.com/sponsors/kylereddoch
[now]: https://kylereddoch.me/now/
