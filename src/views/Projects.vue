<template>
  <div class="projects">
    <h1>Featured Projects</h1>
    <hr/>
    <div class="content">
        <section class="clearfix">
            <h2>ThunderChild</h2>
            <div class="has-text-left">
                <a href="https://thunderchild.netlify.app/" target="_blank" class="aligned">
                <img src="../assets/thunderchild.png">
                </a>
                <div><strong>Code:</strong> <a href="https://github.com/h3x/thunderchild" target="_blank">https://github.com/h3x/thunderchild</a><br />
                <strong>Live site:</strong><a href="https://thunderchild.netlify.app/" target="_blank"> https://thunderchild.netlify.app/ </a><br/>
                <strong>Description:</strong>
                  <p>
                      Thunderchild is a personal project was borne out of frustration. While testing HCP claim reconciliation in my current role, payment files needed to be manually created.
                    This entailed manually editing XML files and doing the calculations by hand. As i asked around, I found that the Customer Relations Team had been operating
                    this same way for years. I built this tool so that I, my team, and others in the company could easily and accuratly generate these payment files for testing and
                    customer demonstrations of our platform.
                  </p>
                  <p>
                    Currently there are about 60 regular users.
                  </p>
                <p>Current Features</p>
                <ul>
                    <li>Single month client Home Care accounting balance and transaction calculations</li>
                    <li>Simple reconciliation tool</li>
                    <li>In app bug reporting</li>
                    <li>Payment file download</li>
                </ul>
                <strong>Technologies used:</strong> Javascript es6, Vue, HTML, CSS, SCSS, Bulma, Email Integration
                </div>
            </div>
        </section>
        <hr />
        <section class="clearfix">
            <h2>Thirty301</h2>
            <div class="has-text-left">
                <a href="https://thirty301.netlify.app/" target="_blank" class="aligned">
                <img src="../assets/thirty301.png">
                </a>
                <div><strong>Code:</strong> <a href="https://github.com/h3x/thirty301" target="_blank">https://github.com/h3x/vue-hive</a><br />
                <strong>Live site:</strong><a href="https://thirty301.netlify.app/" target="_blank"> https://thirty301.netlify.app/ </a><br/>
                <strong>Description:</strong>
                <p>
                    Thirty301 is a fundamental investment guide, allowing users to select public companies to view and help make trading descisions
                    on fundamental data.
                </p>
                <p>
                    <strong>Please note:</strong> This is a work in progress. As such, the API used is a free teir with very restrictive rate limits.
                    If the data does not load, please wait 30 seconds and try again.
                </p>
                <p>
                    Current Features
                    <ul>
                        <li>Symbol and company name search</li>
                        <li>Fundamental data display</li>
                        <li>Closing and daily high for previous 30 days</li>
                    </ul>
                </p>
                <p>
                    Future Features
                    <ul>
                        <li>Firebase connection</li>
                        <li>User auth</li>
                        <li>Watchlist</li>
                        <li>Buy / sell list</li>
                        <ul>
                            <li>Dates per trade</li>
                            <li>Save prices at each trade</li>
                            <li>Calc for profit per trade</li>
                            </ul>
                    </ul>
                </p>
                <strong>Technologies used:</strong> Javascript es6, React, HTML, CSS, SCSS, External APIs
                </div>
            </div>
        </section>
        <hr />
        <section class="clearfix">
            <h2>The Hive</h2>
            <div class="has-text-left">
                <a href="https://thehive.pw" target="_blank" class="aligned">
                <img src="../assets/hive-preview.png">
                </a>
                <div><strong>Code:</strong> <a href="https://github.com/h3x/vue-hive" target="_blank">https://github.com/h3x/vue-hive</a><br />
                <!-- <strong>Live site:</strong><a href="https://thehive.pw" target="_blank"> https://thehive.pw </a><br/> -->
                <strong>Demo</strong><a href="https://www.youtube.com/watch?v=fRIgTARprM4" target="_blank">https://www.youtube.com/watch?v=fRIgTARprM4</a><br />
                <strong>Description:</strong>
                <p>
                  The hive is my interpretation of the board game ‘Hive’. It features private and public chat, an invite system,
                  a database allowing users to continue unfinished games, and some basic stats based off the users’ experience
                </p>
                <p>
                  Please note that due to the age of the project and outdated packages used, the live site is currently unavailable until such time as I can get it updated and running. Feel
                  free to skip arround the youtube video posted to view the built features
                </p>
                <strong>Technologies used:</strong> Node, MongoDB, javascript es6, typescript, Vue, express, HTML, CSS, SCSS, JWT, BCrypt
                </div>
            </div>
        </section>
        <hr />
        <section class="clearfix">
            <h2>Genetic Algorithm in Python3</h2>
            <div class="has-text-left">
                <!-- <a href="https://seagreenharmoniousvirtualmachines.adamaustin.repl.run/" target="_blank" class="aligned"> -->
                <img src="../assets/ga-preview.png" class="aligned">
                <!-- </a> -->
                <div><strong>Code:</strong> <a href="https://github.com/h3x/GA" target="_blank"> https://github.com/h3x/GA</a><br />
                <!-- <strong>Live code:</strong><a href="https://seagreenharmoniousvirtualmachines.adamaustin.repl.run" target="_blank"> https://seagreenharmoniousvirtualmachines.adamaustin.repl.run </a><br/> -->
                <strong>Description:</strong> <p> This was a genetic algorithm i wrote to solve a variation of Einstein's Riddle. The algorithm is fed some clues as to judge the fitness each solution, and then tested against
                    a fitness function. The live site above is hosted on repl.it and obviosuly runs a lot slower than running it on your own machine or server. The hosted version is for demonstration purposes only.
                </p>
                <strong>Technologies used:</strong> Python3
                </div>
            </div>
        </section>
        <hr />
        <section class="clearfix">
            <h2>Cookie-clicker auto clicker</h2>
            <div class="has-text-left">
                <img src="../assets/cc-preview.png" class="aligned">
                <div><strong>Code:</strong> <a href="https://github.com/h3x/auto-clicker" target="_blank"> https://github.com/h3x/auto-clicker</a><br />
                <strong>Description:</strong> <p> This project started as a friendly competition between friends to see who could waste the most time on <a href="https://orteil.dashnet.org/cookieclicker/">cookie-clicker</a>.
                What started out as a laugh soon became a serious competition to see who could automate our clicks with the best effect. This was the result. I pretty soon realised that the bonus cookies that popped up occasionally
                were the key to my success. I added in image recognition to find the bonus cookies and return the cursor to the big cookie, then soon found i needed to figure out how to use threading to offload the image recognition as to not
                interfere with the click rate. While not perfect, it does the job it was born for. I won the competition.

                </p>
                <strong>Technologies used:</strong> Python3
                </div>
            </div>
        </section>
        <hr />
        <section class="clearfix">
            <h2>Project Management Quiz</h2>
            <div class="has-text-left">
                <a href="https://h3x.github.io/PM-quiz/" target="_blank" class="aligned">
                <img src="../assets/quiz-preview.png">
                </a>
                <div><strong>Code:</strong> <a href="https://github.com/h3x/PM-quiz" target="_blank"> https://github.com/h3x/PM-quiz</a><br />
                <strong>Live site:</strong><a href="https://h3x.github.io/PM-quiz/" target="_blank"> https://h3x.github.io/PM-quiz/</a><br/>
                <strong>Description:</strong> <p>This quiz was made to help study the Project Management unit
                    at university. I was able to gather fellow students in the same class to help with contributing
                    questions and answers then open sourced the entire code base so others could benifit if they
                    saw a use for the project i had created.
                </p>
                <strong>Technologies used:</strong> HTML, CSS, Javascript, JQuery
                </div>
            </div>
        </section>
        <hr />
        <section class="clearfix">
            <h2>BattleTanks</h2>
            <div class="has-text-left">
                <a href="https://github.com/h3x/battleTanks" target="_blank" class="aligned">
                <img src="../assets/battletanks-preview.png">
                </a>
                <div><strong>Code:</strong> <a href="https://github.com/h3x/battleTanks" target="_blank"> https://github.com/h3x/battleTanks</a><br />
                <strong>Description:</strong> <p>BattleTanks was a group project worked on by myself and 2 other people.
                    BattleTanks is a multiplayer game played over a local network, or both players using the same keyboard.
                    It was written in the processing environment. To play this game, you will need a copy of Processing with
                    the minim sound library installed ( available at <a href="https://processing.org/">https://processing.org/</a> )
                </p>
                <strong>Technologies used:</strong> Processing
                </div>
            </div>
        </section>
        <hr />
        <section class="clearfix">
            <h2>Portfolio</h2>
            <div class="has-text-left">
                <a href="https://adamjaustin.com" target="_blank" class="aligned">
                <img src="../assets/portfolio-preview.png">
                </a>
                <div><strong>Code:</strong> <a href="https://github.com/h3x/portfolio" target="_blank"> https://github.com/h3x/portfolio</a><br />
                <strong>Live site:</strong><a href="https://adamjaustin.com" target="_blank"> https://adamjaustin.com</a><br/>
                <strong>Description:</strong> <p>This portfolio site. Designed and built for the purposes of showcaseing my experience, code
                    and featured projects.
                </p>
                <strong>Technologies used:</strong> Vue, Node, HTML, CSS
                </div>
            </div>
        </section>
        <hr />
    </div>
  </div>
</template>

<style scoped>
.aligned {
    float: left;
    padding: 20px;
}

</style>
