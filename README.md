# What shoul I know about distributed systems, when I want to be a distributed systems person?

This is from a Twitter conversation, sparked bye a tweet.
<blockquote class="twitter-tweet" lang="en"><p lang="en" dir="ltr">What questions would you put on a phone screen for a distributed systems position?</p>&mdash; ¯\_(ツ)_/¯ (@SeanTAllen) <a href="https://twitter.com/SeanTAllen/status/613135036716568576">June 23, 2015</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

And answered 

<blockquote class="twitter-tweet" lang="en"><p lang="en" dir="ltr"><a href="https://twitter.com/SeanTAllen">@SeanTAllen</a> 1) explain the life of an http request. 2) what does the FLP result teach us? 3) what is a byzantine failure? 4) explain CRDTs</p>&mdash; Mr. Santero (@tsantero) <a href="https://twitter.com/tsantero/status/613222623175008256">June 23, 2015</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

For your convenience a list of the questions on one page, feel free to send PRs with answers or more interesting questions!

1. explain the life of an http request. 
2. what does the FLP result teach us? 
3. what is a byzantine failure? 
4. explain CRDTs
5. explain linearizability. 
6. how does DNS work? 
7. crash-stop vs crash-recovery? 
8. difference between soft and hard real time
9. model GC in an eventually consistent system 
10. discuss clock skew, NTP, and AWS vs metal 
11. what is causal consistency?
12. whats the difference between a vector clock and a version vector? 
13. what is chain replication? 
14. at-most v at-least once
15. model RYOW in an EC system. 
16. why does fail-stop rely on perfect fault detection? 
17. how is this flawed?
18. how does 2PC fail? 
19. how does 3PC fail? 
20. why can't Raft survive byzantine failures?
21. how is 2PC different from fast-consensus? 
22. what do merkel trees accomplish? 
23. how do replicated logs work?
24. discuss an EC system that implement idempotent increments and decrements of counters 
25. why are timeouts common in RPC?
26. push vs poll for stats and why? 
27. advantages and limitations of the actor model? 
28. what is process calculus?
29. what does termination, agreement, and validity guarantee in consensus protocols, respectfully?
30. which systems are best optimized for safety? 
31. liveness? 
32. what are the characteristic differences among the two?
33. why is WAN replication difficult? 
34. which programming languages are best suited for building concurrent systems? why?
35. have you ever been to a RICON? 
36. watched the videos? 
37. what are 3 fundamental diffs between Cassandra and Riak?
38. how can you reduce tail latencies in distributed systems? 
39. why do they matter? 
40. explain set union vs set intersection
41. in your opinion why arent there any decent distributed time series databases on the market? 
42. how can you break paxos?
43. why is a total order reflexive? 
44. what are the fundamentals of atomic broadcast? 
45. what does a POSET guarantee?
46. what is TCP incast? 
47. compare and contrast Kafka, Storm, and Spark 
48. are you familiar with LASP?
49. difficulties of programming concurrent systems in shared memory env? 
50. (last one) do you even know how vector clocks work?

