# Testing

You will be using jest to write unit or endpoint unit tests in your application. Please put all of your tests for your code in the `__tests__` directory. You should get into the habit of ensuring that you have coverage for your code _before submitting a pull request_.

#### Running your tests

Follow these steps when writing tests:

* `cd into` the root of this directory
* `npm run test` to run your test suite
  * _if you're prompted_ select `a` to run tests in watch mode. This will re-run your test suite when you save any file in your application.
* In your terminal you will see a test runner that looks something like this:

  ![Test screenshot](https://tk-assets.lambdaschool.com/bc9ca7b9-4fce-45de-9a16-705cbec062d8_ScreenShot2020-06-25at7.52.52AM.png)

* When you're not actively writing tests its best to close that terminal window so that you don't keep running tests when your files are saved.

#### Coverage <a id="coverage"></a>

> 💡 Code coverage should be a good goal to have and a good starting place. But every application will be different.

* ​[Kent Dodds put it nicely](https://kentcdodds.com/blog/common-testing-mistakes#mistake-number-2-100-code-coverage). Strive for solid coverage as we strive to hand you over well-tested code in which we have extreme confidence.
* To run a coverage report for your application simply run `npm run coverage`.
* You should see a print out in your console that looks like this:

  ​![code coverage](https://tk-assets.lambdaschool.com/5abec98b-2b61-483f-bd85-71002a9f755a_ScreenShot2020-06-25at7.59.14AM.png)

