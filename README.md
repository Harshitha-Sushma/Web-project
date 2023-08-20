# Web-project
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous"/>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div class="container-fluid bg-container">
      <div class="row bg-white">
        <div class="col-12 col-md-6 m-auto bg-white pt-5 pb-5">
          <img
            class="guess-game-img"
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-dynamic-webapps/guess-game-img.png"
          />
          <p class="text-center game-description">
            Find out the right number between 1 to 100
          </p>
        </div>
      </div>
      <div class="row">
        <div class="col-12 guess-bg-container text-center">
          <h1 class="guess-heading">
            Guess The Number
            <img
              class="guess-number-image"
              src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-dynamic-webapps/guess-number-img.png"
            />
          </h1>
          <input type="text" class="user-input" id="userInput" />
          <div>
            <button class="btn btn-info check-guess" onclick="checkGuess()">
              Check
            </button>
          </div>
          <p class="game-result" id="gameResult"></p>
        </div>
      </div>
    </div>
  </body>
</html>
