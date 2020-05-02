# d2p5py
### **Data Driven Processing For Python**

###### _The following is an idea I am considering based on some needs that I have found from wanting to build animated visualizations with large scale datasets._

**p5:** Processing (and it's predecessor Design By Numbers) is downright incredible. Pedegocially, it has what Seymour Papert and Mitch Resnik (I think both) termed, high ceilings and wide walls.  That is, it accomodates all levels of skills from absolute beginning (floor) to very advanced (ceiling) and both can be very expressive with it (wide walls). And, it has a language abstraction for both designers and computer scientists.  While it can do data visualization (see any number of books), the langauge of data visualization has changed, and therefore.  In this particular aspect, while the walls remain high, they are not as wide.

**d3:** d3 is awesome.  It has a language abstraction for data, and it's highly expressive (wide walls).  It's certainly the largest gallery of work I've ever encountered. However, (I find) it's difficult to learn.  To extend the metaphor way past what it was meant for, you need a ladder to get up to where the wall begins.  I don't know.  Maybe it's a loft.

**That said:** Both have performance limitations:  d3 runs in the browser.  And, while Processing is much more robust in terms of power due to the fact that it runs "natively" on your comupter (save p5.js), it still has limitations for very large scale datasets unless you are good with Java which isn't the easist language to learn and (to my knowledge) does not have easy numerical pacakges to work with.

**d2p5py:**  Enter d2p5py. d2 because they aren't documents, but they are data driven.  p5py Processing for native python.  Processing has numpy and the ability to use other packages with syntactic sugar to make the visualisation of large datasets not only possible but combined with p5's API, accessable in the way that p5 was built do be.  Python is also one of the leading data science languages and to my knowledge the only one that has (sci ruby is on it's way!) packages which span hardware and software.
