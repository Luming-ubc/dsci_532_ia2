# Individual assignment 2

The individual task is focused on the map of the application.
The deployed partial app is hosted here https://dsci532-2022-ia2-lyang.herokuapp.com/.

Steps to reproduce:

1. `git clone https://github.com/Luming-ubc/dsci_532_ia2.git`
2. `cd dsci_532_ia2`
3. `heroku create --stack container dsci532-2022-ia2-lyang`
4. `git push heroku main`
5. Wait ~15 min for the build to finish.
6. `heroku ps:scale web=1`
7. Navigate to `https://you-heroku-site.herokuapp.com` in your browser
