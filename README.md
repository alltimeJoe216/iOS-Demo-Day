# iOS Demo Day

## Requirements

1. Fork and clone the repository
2. Create a branch for Unit1 or Unit4
3. Add your Team Name / Team Members and make a commit
4. Create a pull request (PR) and **tag your TL and Instructor**
5. **Add your presentation content**
    1. Slide deck (4 required slides)
    2. Links
    3. Answer all questions 
    4. YouTube demo video (1-2 min max)
6. Polish your Github Code repository
    1. Add screenshots and an overview to your GitHub Code Repository
    2. You should make that repository the "Public Portfolio" for your project
    3. Look at [John Sundell's Splash project](https://github.com/JohnSundell/Splash) for inspiration (code, images, GIFs)


## Links

* App Name: "Binge It, Baby"
* Team: N/A
* Github Code: https://github.com/alltimeJoe216/BingItBaby.git
* Github Proposal: https://trello.com/b/htD2270d/binge-it-baby
* Trello/Github Project Kanban: n/a
* Test Flight Signup (Recommended): n/a
* YouTube demo video (Recommended): n/a

## Hero Image



## Questions (Answer indented below)

1. What was your favorite feature to implement? Why?

    Implementing the carousel affect was a lot of fun! 

2. What was your #1 obstacle or bug that you fixed? How did you fix it?

    Realizing data can't be transfered via delegates when using tab bars was a huge bummer and 
  
3. Share a chunk of code (or file) you're proud of and explain why.

      let movieCell = homePageController?.movieList[indexPath.row]
           
            cell.movieList = movieCell
            cell.backgroundColor = .clear
            cell.contentView.layer.cornerRadius = 10
            cell.contentView.layer.borderWidth = 1.0
            cell.contentView.layer.borderColor = UIColor.black.cgColor
            cell.contentView.layer.masksToBounds = true;
            cell.layer.shadowColor = UIColor.purple.cgColor
            cell.layer.isOpaque = true
            cell.layer.shadowOffset = CGSize(width: 0, height: 0.0)
            cell.layer.shadowRadius = 10.0
            cell.layer.shadowOpacity = 1.0
            cell.layer.masksToBounds = true

            return cell
            
     This chunk of code was special to me because it was the first time I created a custom cell outside of class. Found some really neat properties to mess around with!
  
4. What is your elevator pitch? (30 second description your Grandma or a 5-year old would understand)

    Are you sick of wasting time flicking through Netflix looking for something worthy to watch? Tired of having your boo over for Netflix and Chill and it ends up being just scroll through Netflix and chill? Binge It, Baby solves all your excess scrolling needs. Featuring thousands of movies (actually like 12), you can scroll through the app one time in the morning, add movies to your watchlist and come back later on when it's time to binge your favorite movies! 
  
5. What is your #1 feature?

    Carousel Collection View
  
6. What are you future goals?

        It would be cool to be able to connect to your other streaming apps to actually watch the movie. 

## Required Slides (Add your Keynote to your PR)

1. App Name / Team Slide
2. Elevator Pitch
3. Demo
4. Future Goals

## Slide Requirements

1. 50 pt font minimum
2. Be concise — don't write sentences/paragraphs (put these in your slide notes for speaking)
3. 3-6 bullets maximum per slide
4. Do the squint test (can you read the text if you squint, if so, make the font bigger)
6. Images are always welcome
7. Do the Grandma Test (Would your Grandma understand you?)

### Optional Slides

1. Blooper: What's a funny bug or blooper? (screenshots/GIFs please)
2. Revenue Model: If the app was your sole source of income, how would you monetize it?

## Presentation Format

**7 minutes/team**

* 4 minute presentation (5 minute hard cap)
* 3 minutes of questions

We have ~12 teams presenting today — please practice your presentation with a timer (as a team), and make sure you fit within the time limit.

Plan on having one person present the slides and live demo. Please practice your presentation in front of a mirror or with your team 2-5 times. Have the app running and visible (Simulator or QuickTime) so you can quickly transition between slides and live demo.

* App Name / Team Slide (30 seconds)
* Elevator Pitch Slide (60 seconds)
* Live Demo (2 minutes)
* Future Goals (30 seconds)
* Questions (3 minutes)
