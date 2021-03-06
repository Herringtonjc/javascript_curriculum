### Introduction
We're going to make a simple implementation of grade-school classic "rock paper scissors".  If you don't know what that is check the [wikipedia article](https://en.wikipedia.org/wiki/Rock%E2%80%93paper%E2%80%93scissors) or [this](https://www.wikihow.com/Play-Rock,-Paper,-Scissors) ridiculous step-by-step.  For the moment we're just going to play the game from the browser console, but we will revisit it and add a front end later so don't forget to keep the code on GitHub! You might notice some 'view in browser' links in the student solutions - this is coming in a later lesson.  When you get there don't forget to come back and add  your link!

### Assignment

<div class="lesson-content__panel" markdown="1">
1. Start a new git repo for your project.
2. Create a blank HTML document with a script tag.  This game is going to be played
    completely from the console, so don't worry about putting anything else in there.
3. Your game is going to play against the computer, so begin with a function called `computerPlay` that will randomly return either 'Rock', 'Paper' or 'Scissors'.  We'll use this function in the game to make the computer's play.
4. Write a function that plays a single round of Rock Paper Scissors.  The function should take two parameters - the `playerSelection` and `computerSelection` - and then return a string that declares the winner of the round like so: `"You Lose! Paper beats Rock"`
   1. make your function case insensitive (so users can input `rock`, `ROCK`, `RocK` or any other variation)

   2. __Important note:__ you want to `return` the results of this function call, _not_ `console.log()` them.  To test this function console.log the results:

      ~~~javascript
      function playRound(playerSelection, computerSelection) {
      	// your code here!
      }

      const playerSelection = 'rock'
      const computerSelection = computerPlay()
      console.log(playRound(playerSelection, computerSelection))
      ~~~

      ​
5. Write a NEW function called `game()`. Use the previous function _inside_ of this one to play a 5 round game that keeps score and reports a winner or loser at the end.
   1. At this point you should still just be using `console.log()` to display the results of each round and the winner at the end.
   2. Use `prompt()` to get input from the user. [Read the docs here if you need to.](https://developer.mozilla.org/en-US/docs/Web/API/Window/prompt)
   3. Feel free to re-work your previous functions if you need to.  Specifically, you might want to change the return value to something more useful.
   4. Feel free to create more "helper" functions if you think it would be useful.

</div>

### Student Solutions
Submit a solution with a pull request to this [file](https://github.com/TheOdinProject/javascript_curriculum/blob/master/JS101/fundamentals/rock-paper-scissors-project.md) on the Javascript Curriculum github repository. See the section on [Contributing](http://github.com/TheOdinProject/curriculum/blob/master/contributing.md) for how.

- Add your solution below this line!
- [Ngo Van Huong's Solution](https://github.com/ngovanhuong94/rock-paper-scissors) - [View in Browser](https://ngovanhuong94.github.io/rock-paper-scissors/)
- [Ochuko's Solution] (https://github.com/ochuko56/rock-paper-scissors)
- [Antony's Solution](https://github.com/AntonyOtero/rock-paper-scissors)
- [Typhoon's Solution](https://github.com/typhoon93/rock-paper-scissors) - [View in Browser](https://typhoon93.github.io/rock-paper-scissors/)
- [autumnchris's Solution](https://github.com/autumnchris/rock-paper-scissors) - [View in Browser](https://autumnchris.github.io/rock-paper-scissors)
- [Nicholas Ewing's Solution](https://github.com/NicholasEwing/rock-paper-scissors)
- [jstnlester's Solution](https://github.com/jstnlester/rock-paper-scissors) - [View in Browser](https://jstnlester.github.io/rock-paper-scissors/)
- [Erick Jansen's GUI solution](https://github.com/Ey-Jay/Rock-Paper-Scissors-Game) - [View in browser](https://ey-jay.github.io/Rock-Paper-Scissors-Game/)
- [Simon Tharby's UI solution](https://github.com/jinjagit/RockPaperScissors) - [View in browser](https://jinjagit.github.io/RockPaperScissors/)
- [Douglasbsx Console Solution](https://github.com/douglasbsx/rock-paper-scissors) - [View in Browser](https://douglasbsx.github.io/rock-paper-scissors/) - [UI Version](https://github.com/douglasbsx/rock-paper-scissors-ui) - [View in Browser](https://douglasbsx.github.io/rock-paper-scissors-ui/)
- [Mark Bungeroth's Solution](https://github.com/mbungeroth/rockpaperscissors) - [View in Browser](https://mbungeroth.github.io/rockpaperscissors/)
- [Ed Magalhaes' solution](https://github.com/EdMagal/RockPaperScissor)
- [Tarah Nixon's Solution](https://github.com/ErraticCreation/rock-paper-scissors)
- [seoul2045's console solution](https://github.com/seoul2045/rockpaperscissor/blob/master/rockPaperScissor_console.html) - [UI version](https://seoul2045.github.io/rockpaperscissor/)
- [Lee Rogers's solution UI version](https://github.com/eleerogers/RPS) - [View in Browser](https://eleerogers.github.io/RPS/)
- [mthsgrc's Solution](https://github.com/mthsgrc/rockpaperscissors-game) - [View in Browser](https://mthsgrc.github.io/rockpaperscissors-game)
- [Zachary Coxe's solution](https://github.com/faultde/RPSv1) - [View in Browser](https://faultde.github.io/RPSv1/)
- [Adrien Pardo's console solution](https://github.com/Shieboo/rock-paper-scissors) - [UI version](https://github.com/Shieboo/rock-paper-scissors-ui)
- [Andrew's solution](https://github.com/andrewr224/rock-paper-scissors) - [View in browser](https://andrewr224.github.io/rock-paper-scissors/)
- [Almyra's Solution](https://github.com/almyrav/rock-paper-scissors)
- [Emmit's solution](https://github.com/FenrirETS/rock-paper-scissors)
- [Webop's console solution](https://github.com/webop/rock-paper-scissors) - [UI solution](https://github.com/webop/rock-paper-scissors-ui) - [View in browser](https://webop.github.io/rock-paper-scissors-ui/)
- [Ivanv257's solution](https://ivanv257.github.io/Rock-Paper-Scissors-JavaScript-Project/) - [View in browser](https://ivanv257.github.io/Rock-Paper-Scissors-JavaScript-Project/)
- [Tony Nyagah's solution](https://github.com/TonyNyagah/rock-paper-scissors)
- [hypnagogiasmic's solution](https://github.com/hypnagogiasmic/rps) - [View in browser](https://rawgit.com/hypnagogiasmic/rps/master/rps-new.html)
- [Kerstin Wagner's solution](https://github.com/KWagner91/rock-paper-scissors)
- [ayanlehd's solution](https://github.com/ayanlehd/rock_paper_scissors)
- [Jon Yoo's solution](https://github.com/jonyoowa/rock-paper-scissors-browser) - [View in browser](https://jonyoowa.github.io/rock-paper-scissors-browser/)
- [D1789's solution](https://github.com/D1789/RPS1) - [View in browser](https://rawgit.com/D1789/RPS1/master/index.html)
- [Edmond Alosa's solution](https://github.com/eddalosa/rockPaperScissor) - [View in browser](https://eddalosa.github.io/rockPaperScissor/)
- [Paul-EN's solution](https://github.com/Paul-EN/rock-paper-scissors/blob/master/index.html) - [View in browser](https://paul-en.github.io/rock-paper-scissors/) - [UI version](https://github.com/Paul-EN/rock-paper-scissors-v2) - [View in browser](https://paul-en.github.io/rock-paper-scissors-v2/)
- [Alexander John's solution](https://github.com/alexander-john/rock-paper-scissors) - [View in browser](https://alexander-john.github.io/rock-paper-scissors/)
- [Kerstin Wagner's solution](https://github.com/KWagner91/rock-paper-scissors) - [View in browser](https://kwagner91.github.io/)
- [Johan Morin's console solution](https://github.com/MorrisMalone/rock_scissors_paper.git) - [UI solution](https://github.com/MorrisMalone/rock_scissors_paper) - [View in browser](https://morrismalone.github.io/rock_scissors_paper/)
- [Matt Claghorn's solution](https://github.com/Claggy/rock-paper-scissors) - [View in browser](https://claggy.github.io/rock-paper-scissors/) - [UI version](https://github.com/Claggy/rock-paper-scissors-ui) - [View in browser](https://claggy.github.io/rock-paper-scissors-ui/)
- [Bartek Butrym's solution](https://github.com/BartekButrym/rock-paper-scissors)
- [Fabien Kovacic's solution](https://github.com/Fabious/rock-paper-scissors) - [View in browser](https://fabious.github.io/rock-paper-scissors/)
- [mindovermiles262's Solution](https://github.com/mindovermiles262/odin-js101-solutions/tree/master/project-rock-paper-scissors)
- [Jonathan Yiv's solution](https://github.com/JonathanYiv/rock-paper-scissors) - [View in browser](https://jonathanyiv.github.io/rock-paper-scissors/)
- [Uglješa Ijačić's solution](https://github.com/ugitch/rock-paper-scissors)
- [Samuel Master's UI solution](https://github.com/redeyetuning/rock-paper-scissors/) - [View in browser](https://redeyetuning.github.io/rock-paper-scissors/)
- [SarfrazAnjum Solution](https://github.com/SarfrazAnjum/Rock-Paper-Scissors)
- [Bojana Karakacev's solution](https://github.com/bojana12/rock-paper-scissors) - [View in browser](https://bojana12.github.io/rock-paper-scissors/dist/) - [UI version](https://github.com/bojana12/rock-paper-scissors-UI) - [View in browser](https://bojana12.github.io/rock-paper-scissors-UI/dist/)
- [James Moores's Gui solution](https://rawgit.com/James-N-M/rock-paper-scissors/master/index.html)
- [Jmooree30's solution](https://github.com/jmooree30/rock-paper-scissors) - [View in browser](https://jmooree30.github.io/rock-paper-scissors/)
- [Luján Fernaud's solution](https://github.com/lujanfernaud/js-rock-paper-scissors) - [View in browser](http://lujanfernaud.com/js-rock-paper-scissors/)
- [Clifford Minks's console solution](https://github.com/xxerror500xx/TOP_RPSGame.git) - [View in browser](https://xxerror500xx.github.io/TOP_RPSGame/)
- [Nate Dimock's solution](https://github.com/Flakari/rock-paper-scissors) - [View in browser](https://flakari.github.io/rock-paper-scissors/) - [GUI Solution](https://github.com/Flakari/rock-paper-scissors-gui) - [View in browser](https://flakari.github.io/rock-paper-scissors-gui/)
- [leosoaivan's solution](https://github.com/leosoaivan/rockpaperscissor)
- [ThirtyThreeB's solution](https://github.com/ThirtyThreeB/rock-paper-scissors) - [View in browser](https://thirtythreeb.github.io/rock-paper-scissors/)
- [PongtheGreat's solution](https://github.com/PongtheGreat/RPS) - [View in browser](https://pongthegreat.github.io/RPS/)
- [codyloyd's solution](https://github.com/codyloyd/odin-rock-paper-scissors) - [GUI version!](http://codyloyd.com/odin-rock-paper-scissors/)
- [Tshepo Mohlamonyan's solution](https://github.com/blavkboy/rock_paper_scissors.git)
- [g0-0py's solution](https://github.com/g0-0py/Rock-Paper-Scissors) - [View in browser](https://g0-0py.github.io/Rock-Paper-Scissors/)  |  [GUI](https://github.com/g0-0py/Rock-Paper-Scissors-GUI) - [View in browser](https://g0-0py.github.io/Rock-Paper-Scissors-GUI/)
- [Kimberlee's solution](https://github.com/KimDube/web-development/tree/master/rock-paper-scissors) - [View in browser](https://kimdube.github.io/web-development/rock-paper-scissors/)
- [SamJamCul's solution](https://github.com/SamJamCul/rock-paper-scissors) - [View in browser](https://samjamcul.github.io/rock-paper-scissors/)
- [Djokole's solution](https://github.com/djokole/RPS) - [View in browser](https://djokole.github.io/RPS/)
- [artkol's solution](https://github.com/artkol/simple-rps-game) - [View in browser](https://artkol.github.io/simple-rps-game/)
- [Shanemcc94's solution](https://github.com/shanemcc94/rock-paper-scissors) - [View in browser](https://shanemcc94.github.io/rock-paper-scissors/)
- [dejanmijatovic's solution](https://github.com/Anhatel/rock-paper-scissors)
- [technicolor1's solution](https://github.com/technicolor1/odin-rockpaperscissors) - [View in browser](https://technicolor1.github.io/odin-rockpaperscissors/)
- [Jakub Cisowski's solution](https://github.com/arashin1337/rock-paper-scissors) - [View in browser](https://arashin1337.github.io/rock-paper-scissors/)
- [Alexander Luna's solution](https://github.com/Mycroft1891/my-odin-project/tree/master/web-development-101/rps) - [View in browser](https://mycroft1891.github.io/my-odin-project/web-development-101/rps/index.html)
- [Niko Caron's solution](https://github.com/ncaron/RPSLS) - [View in browser](https://ncaron.github.io/RPSLS/)
- [Dareon4's solution](https://github.com/Dareon4/rock-paper-scissors) - [View in browser](https://dareon4.github.io/rock-paper-scissors/)
- [Agnieszka'a solution](https://github.com/elPetit69/gui-rock-paper-scissors) - [View in browser](https://elpetit69.github.io/gui-rock-paper-scissors/)
- [Eduardo Massarani's solution](https://github.com/edmassarani/the-odin-project/tree/master/projects/jankenpon/gui-version) - [View in browser](https://edmassarani.github.io/the-odin-project/projects/jankenpon/gui-version/)
- [Nick Leake's solution](https://github.com/nleake/odin-js-rockPaperScissors)
- [Javier Machin's solution](https://github.com/Javier-Machin/RockPaperScis) - [View in browser](https://javier-machin.github.io/RockPaperScis/)
- [CurmudJim's solution](https://github.com/CurmudJim/top_rps_js) - [View in browser](https://curmudjim.github.io/top_rps_js/)
- [Encolpius's solution](https://github.com/Encolpius/rock-paper-scissors) - [View in browser](https://encolpius.github.io/rock-paper-scissors/)
- [PaullyFIRE's solution](https://github.com/paullyFIRE/RockPaperScissors) - [View in browser](https://paullyfire.github.io/RockPaperScissors/)
- [vartanbeno's solution](https://github.com/vartanbeno/rock-paper-scissors) - [View in browser](https://vartanbeno.github.io/rock-paper-scissors/)
- [Alexey Leonov's solution](https://github.com/axelerleo/rock-skissors-paper) - [View in browser](https://axelerleo.github.io/rock-skissors-paper/)
- [Fabio Oliveira's solution](https://github.com/ffabiorj/rock_paper_scissors) - [View in browser](https://cdn.rawgit.com/ffabiorj/rock_paper_scissors/dab5e260/index.html)
- [Benny Thai's solution](https://github.com/Deckins/rock_paper_scissors) - [View in browser](https://deckins.github.io/rock_paper_scissors/)
- [Franklyn Afeso's solution](https://github.com/afeso/janken) - [View in browser](https://afeso.github.io/janken_ui)
- [Matt Hagner's solution](https://github.com/hagnerd/improved-rock-paper-scissors) - [View in browser](https://hagnerd.github.io/improved-rock-paper-scissors/)
- [WausauBill's Solution](https://github.com/WausauBill/WausauBill.github.io/tree/master/the_odin_project/roshambo) - [View in Browser](https://wausaubill.github.io/the_odin_project/roshambo/index.html)
- [Ryoma's solution](https://github.com/ryozume/rock_paper_scissors) - [View in browser](https://ryozume.github.io/rock_paper_scissors_withJS/)
- [bradabayor's Solution](https://github.com/bradabayor/rock-paper-scissors) - [View in Browser](https://bradabayor.github.io/rock-paper-scissors)
- [HSaad's solution](https://github.com/HSaad/rock-paper-scissors) - [View in browser](https://hsaad.github.io/rock-paper-scissors/)
- [jmurinello's solution](https://github.com/jmurinello/rock-scissors-paper)
- [Cody Selman's solution](https://github.com/CodySelman/rock-paper-scissors) - [View in browser](https://codyselman.github.io/rock-paper-scissors/index.html)
- [Zach Coursey's solution](https://github.com/zcoursey22/rock-paper-scissors) - [View in browser](https://zcoursey22.github.io/rock-paper-scissors)
- [Nikhil Patel's Solution](https://github.com/nikhilpatel87/rock-paper-scissors/blob/master/index.html) - [View in browser](https://nikhilpatel87.github.io/rock-paper-scissors/)
- [Jacob Folley's solution](https://github.com/jacob-folley/rock_paper_scissor) - [View in browser](https://jacob-folley.github.io/rock_paper_scissor/)
- [Ivan Martinez' Solution](https://github.com/ivanmaru86/rock-paper-scissors)
- [Jimmy's solution](https://github.com/pty5io/Rock-Paper-Scissors) - [View in browser](https://pty5io.github.io/Rock-Paper-Scissors/)
- [Jamie's Solution](https://github.com/Zorafins/rock-paper-scissors) - [View in browser](https://zorafins.github.io/rock-paper-scissors)
- [Balake's Solution](https://github.com/Balake/rock-paper-scissors/blob/master/index.html) - [View in browser](https://balake.github.io/rock-paper-scissors/)
- [Joe Weston's Solution](https://github.com/joeeeeeeeeeeeee/rock-paper-scissors) - [View in browser](https://joeeeeeeeeeeeee.github.io/rock-paper-scissors)
- [Suraj's solution](https://github.com/surajsingla333/rock-paper-scissors) - [View in browser](https://surajsingla333.github.io/rock-paper-scissors)
- [Benny's Solution](https://github.com/Deckins/rock_paper_scissors) - [View in browser](https://deckins.github.io/rock_paper_scissors/)
- [Aziz Yakubov's solution](https://github.com/azizyakubov/rock-paper-scissors) - [View in browser](https://azizyakubov.github.io/rock-paper-scissors/)
- [Onur's solution](https://github.com/deksudo/RockPaperScissors) - [View in browser (UI version)](https://deksudo.github.io/RockPaperScissors/)
- [Lucas Manzano's solution](https://github.com/lucasmfarias1/rock-paper-scissors) - [View in browser](https://lucasmfarias1.github.io/rock-paper-scissors/)
- [Nick Prieto's Solution](https://github.com/NickWhoCodes/RockPaperScissors) - [View in browser](https://github.com/NickWhoCodes/RockPaperScissorsGUI)
- [Steve Cooke's solution](https://github.com/cook1e20/rockPaperScissors) - [View in browser](https://cook1e20.github.io/rockPaperScissors/)
- [Nicole C's solution](https://github.com/nychinn/js-experiments/tree/master/projects/jankenpon) - [View in browser](https://nychinn.github.io/js-experiments/projects/jankenpon)
- [Natalie Aldrich's solution](https://github.com/nataliealdrich/rock-paper-scissors) - [View in browser](https://nataliealdrich.github.io/rock-paper-scissors/)
- [keyur22's console solution](https://github.com/keyur22/Rock-Paper-Scissors-Console-Version-) - [View in browser](https://keyur22.github.io/Rock-Paper-Scissors-Console-Version-/)
- [keyur22's UI solution](https://github.com/keyur22/Rock-Paper-Scissors-UI-Version-) - [View in browser](https://keyur22.github.io/Rock-Paper-Scissors-UI-Version-/)
- [Shing Wong's solution](https://github.com/ayoshing/rock-paper-scissor) - [View in browser](https://ayoshing.github.io/rock-paper-scissor/)
- [Kevin's Solution](https://github.com/super-kebin/rock_paper_scissors)
- [JohnPiatras' Solution](https://github.com/JohnPiatras/rock-paper-scissors) - [View in browser](https://johnpiatras.github.io/rock-paper-scissors), [GUI version](https://github.com/JohnPiatras/rock-paper-scissors-gui) - [View in browser](https://johnpiatras.github.io/rock-paper-scissors-gui/)
- [3lux's solution](https://github.com/3lux/rock-paper-scissors) - [View in browser](http://3lux.github.io/rock-paper-scissors)
- [Hana Klingova's solution](https://github.com/hanny21/rock_paper_scissors) - [View in browser](https://hanny21.github.io/rock_paper_scissors/)
- [Punnadittr's solution](https://github.com/punnadittr/rockpaperscissors) - [View in browser](https://punnadittr.github.io/rockpaperscissors/)
- [Vlado's solution](https://github.com/Vlado212/Papir_skare_kamen)
- [Faris Ibrahim's solution](https://github.com/procusr/rock-paper-scissors)
- [Jarred Herrington's Console Solution](https://github.com/Herringtonjc/rock-paper-scissors) - [View in Browser](https://herringtonjc.github.io/rock-paper-scissors/)
- [Jarred Herrington's UI Solution](https://github.com/Herringtonjc/rock-paper-scissors-ui) - [View in Browser](https://herringtonjc.github.io/rock-paper-scissors-ui/)
- [mojotron's Solution](https://github.com/mojotron/rock-paper-scissors) - [View in Browser](https://mojotron.github.io/rock-paper-scissors/)
- [Matthias' solution](https://github.com/MatthiasStra/Rock_Paper_Scissors)
- [Gabriel Fendt's solution](https://github.com/fendtg4/Rock-Paper-Scissors) - [View in Browser](https://fendtg4.github.io/Rock-Paper-Scissors/)
- [Tony Chidi's solution](https://tn-rock-paper-scissors.herokuapp.com/) - [View in Browser](https://tn-rock-paper-scissors.herokuapp.com/)
- [kwambugu's Solution](https://github.com/kwambugu/rock-paper-scissors)
- [mjparker's Console Solution](https://github.com/mjparker/rock-paper-scissors)
- [nith05's solution](https://github.com/nith05/rock-paper-scissors)
- [Ross' solution](https://github.com/RossTrang/rock-paper-scissors) - [Play Text version](https://rawgit.com/RossTrang/rock-paper-scissors/master/rps-text.html) - [Play GUI version](https://rawgit.com/RossTrang/rock-paper-scissors/master/rps-gui.html)
- [Pranshu's solutions](https://github.com/pranshugaba/rock_paper_scissors)
- [Ol4er's solutions](https://github.com/ol4er/RPS)
- [Allan Burns' solution](https://github.com/allanlburns/rock-paper-scissors/blob/master/rock_paper_scissors.html)
- [IvanaGoSt's solution](https://github.com/IvanaGoSt/rock-paper-scissors)
- [Daniel Mau's Solution](https://github.com/dbm19/RPS)
- [Fabricio Garcia's solution](https://github.com/fabricI0/rock-paper-scissors)
- [James Thomson's solution](https://github.com/jthomsonx/rockpaperscissors_js)
- [Giorgi Shengelaia's solution](https://github.com/supuun/jeirani)
- [Daniel Ortea's Solution](https://github.com/D-Ortea/rock-paper-scissors) - [View in Browser(text)](https://d-ortea.github.io/rock-paper-scissors/v0/index.html) - [View in Browser(GUI)](https://d-ortea.github.io/rock-paper-scissors/v1/index.html)
