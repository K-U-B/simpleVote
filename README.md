# simpleVote
Simple scalable voter platform, inspired by question a friend asked some time ago

# Design
Based on PHP with Apache
  * Mobile App send HTTP request for vote
  * Apache/PHP answers in HTTP after storing vote on three upstream MySQL servers
  * MySQL servers push aggregated votes to spine MySQL servers
  * Root MySQL servers to read out data and replicate (questions)
  
  
