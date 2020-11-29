<template>
  <section id="documentation" class="hello section">
    <div class="columns">
        <div class="column is-three-quarters container">
            <h1 class="title">How to Use</h1>
            <h1 class="subtitle">
                👉 IMPORTANT!! Please read everything on this page for successful use of the application.
            </h1>
            <div  class="instruction-section">
                <h1 class="title is-5">⚠️  Disclaimer</h1>
                <p>
                    I am by no means responsible for any usage of this application. Use it on your own behalf. I'm also not responsible if your accounts get banned due to extensive use of this tool.
                </p>
            </div>
            <div class="instruction-section">
                <h1 class="title is-5">🔥 Instadroid’s purpose</h1>
                <p>
                    Increase organic traffic to your page by automating Instagram interactions: <strong>Liking</strong>, <strong>Following</strong>, and <strong>Unfollowing</strong> on your phone. This will rapidly grow your Instagram page when paired with great and consistent content from you (brand/company/creator).
                </p>
            </div>
            <div class="instruction-section content">
                <h1 id="set_up" class="title is-5">📃 Automation Set Up</h1>
                <strong>Instdroid is best used on a dedicated phone.</strong>
                <p>
                    <a href="https://www.amazon.com/Google-Pixel-Memory-Phone-Unlocked/dp/B07P8MQHSH/ref=as_li_ss_tl?dchild=1&keywords=google+pixel+3&qid=1598178433&sr=8-3&linkCode=ll1&tag=danield04-20&linkId=034ea368b743e785a76911f8b6f51645&language=en_US">Google Pixel 3</a> is currently the only tested Android phone that works properly with this app. Join our <a href="https://facebook.com/groups/298146074618530/">FB group</a> to submit reports if you have another phone model that works. This app is best used with an extra phone that is plugged in 24/7 & connected to WiFi. You can also manually run interactions, but messages or phone calls can interrupt the automation process.
                <ol type="1">
                    <li>
                        Go to Settings > System > Developer Options > Flip On ‘Stay Awake’
                    </li>
                    <li>
                        Go to Settings > Accessibility > Under ‘Downloaded services’ > Click this app > Turn on ‘Use Service’ (Skip this if you already did this in app set up)
                    </li>
                    <li>
                        Make sure you are logged into Instagram (up to 5 accounts with Pro)
                    </li>
                    <li>
                        Go to Settings > Under Application Settings >
                        Click ‘Your Instagram Users’ to add your Instagram handles from the previous step (up to 5 accounts with Pro)
                    </li>
                    <li>
                        OPTIONAL - Go to Settings > Under ‘Application Settings’
                        Click ‘Safe List’ to add friends to a list that prevents the app from unfollowing them
                    </li>
                </ol>
                </p>
            </div>
            <div class="instruction-section content">
                <h1 class="title is-5">
                    🕛 Automated Activities
                </h1>
                <p>
                    Properly <a href="#set_up">set up</a> the phone or automation will fail. Create a list of automated activities in the home page. This app will self-navigate to Instagram and perform the actions. Exiting Instagram will stop the current activity. Check Logs for successful or failed activities. Report repeatedly failed activities to our <a href="https://facebook.com/groups/298146074618530/">FB group</a>. It is important to leave the phone by itself while actions are carried.
                </p>
                <h3 class="title is-6">
                    Like By Tag
                </h3>
                <ol>
                    <li>
                        Enter a hashtag that you can find on Instagram. Entering a hashtag that doesn't exist will cause the action to fail.
                    </li>
                    <li>
                        Enter how many posts you want to like in this activity.
                    </li>
                    <li>
                        Enter whether you want to follow users in the recent or top feed. I recommend the <b>recent feed</b> for most cases.
                    </li>
                    <li>
                        Schedule a time.
                    </li>
                </ol>
                <h3 class="title is-6">
                    Follow By Tag
                </h3>
                <ol>
                    <li>
                        Enter a hashtag that you can find on Instagram. Entering a hashtag that doesn't exist will cause the action to fail.
                    </li>
                    <li>
                        Enter how many users you want to follow in this activity.
                    </li>
                    <li>
                        Enter whether you want to follow users in the recent or top feed. I recommend the <b>recent feed</b> for most cases.
                    </li>
                    <li>
                        Schedule a time.
                    </li>
                </ol>
                <h3 class="title is-6">
                    Unfollow
                </h3>
                <ol>
                    <li>
                        Enter how many users you want to unfollow in this activity.
                    </li>
                    <li>
                        Enter whether you want to follow users in the recent or top feed. I recommend the <b>recent feed</b> for most cases.
                    </li>
                    <li>
                        Schedule a time.
                    </li>
                </ol>
            </div>
            <div  class="instruction-section content">
                <h1 class="title is-5">👥 Join our facebook group!</h1>
                <ul>
                    <li>
                        <a href="https://facebook.com/groups/298146074618530/">FB group</a>
                    </li>
                    <li>
                        Discuss growth strategies and interaction limits to avoid actions being blocked
                    </li>
                    <li>
                        Submit bug reports and feature requests
                    </li>
                    <li>
                        Keep up to date about new releases & new features
                    </li>
                </ul>
            </div>
        </div>        
    </div>
  </section>
</template>

<script>
export default {
  name: 'Instructions',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.instruction-section {
    margin-top: 2em;
}
</style>
