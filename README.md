# cs-360-Mobile-architect-planning
# Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
        This app was designed to allow potential users to catalog their weight in an easy to read list. Information put in
    could then be tied to the user's account so only they could see their inputs. Users can enter the date themselves
    incase they have a format preference and entries can be editted by simply tapping the row you wish to change. A user 
    could also setup a goal weight above their list and recieve SMS notifications (if allowed) when they've entered a 
    weight matching or "exceeding" their goal. 
# What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
        To accomplish the goals set out for this app we required a login screen along with a listing screen, setting screen, 
    and finally a weight input screen. The login and settings screens were kept simple to ensure users couldn't get lost 
    or confused. The listing screen was made to keep user functions centered. Our floating addition button was chosen to 
    increase visibility without increasing the size of other elements such as a toolbar. Having the user's goal above their
    weight listing allows users to easily reference their goal for comparison. Finally, the list's information icons and
    delete button were designed to be easily clicked without the need of a pen or super precise pushing by the user. This
    way users can have an easier time editting certain pieces of information. I'm uncertain how successful my design is 
    since it hasn't been tested by anyone other than myself, however personally I believe I've designed something that's 
    easy for anyone to learn with ease.
# How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
        If I'm being honest I didn't have a solid strategy for when it came to coding my application. The main idea I was working
    on was building one feature in its entirety before moving on. I coded the login screen, the acount list, and the repository 
    all together so that I could test their functionality and all it entails. I followed this same process for each feature
    present on our application until there was nothing else to work on besides the settings page. In many ways this strategy
    worked out for me, since building each feature ended up leading to the next one as they began to interact. Depending on
    my future projects this same strategy could be used to breakup a larger project into more managable pieces. 
# How did you test to ensure your code was functional? Why is this process important and what did it reveal?
        Once I had the basis of a function's code down I would attempt to start the app and interact with the newly setup or
    editted function. Initial tests would see if we can accomplish the goal of the function normally. If for any reason 
    the app crashed or the function didn't pan out as expected then I would go back and look at that function's code specifically
    until I fixed the issue. Testing is one of the most important parts of the development lifecycle not only because 
    you get to see first hand if your app works, but so you can also throw off the wall situations at your app to see 
    how it handles malicious interactions. The more strenuous your tests are the more bugs and loopholes you'll find in 
    your code that can then be polished away. 
# Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
        When I was initially designing how I wanted the application to look I considered having a screen dedicated to a 
    line graph using the data users input as the two axis. When it finally came time to develop the screens and their 
    components I found the data grid incredibly complicated all on its' own. With the deadlines we had in place for 
    iteration submission it was decided that I would forgo the graph screen in favor of perfecting data grid functionality. 
    I also found that I needed a seperate screen for data editting so I could put a destinction between new input 
    data and changed data otherwise each edit eneded up adding the data as a new entry. 
# In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
        If it's not a little obvious by my mentioning of it throughout most of these questions, I have to say the data 
        grid is my proudest compenent in this application. I went through several java sites, video tutorials, and question 
        forums in order to understand how to build a seperate layout for list items that could then be inserted into a 
        recyclerview that could then be programmed to individually respond to user interactions. By the end of the montage 
        of research I had successfully made a grid style list that could both be scrolled endlessly if data exceeded the
        screen size, and allowed users to add, edit, and delete any row of data they input. I know this questions says 
        experience and knowledge but I'd like to think this shows my skills in research/data gathering. With this skill 
        I can potentially learn anything necessary to accomplish a task given to me including develop an app I know little about. :)
