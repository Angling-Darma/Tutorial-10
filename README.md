## Understanding how it works.
It works by spawning executor that will execute the given function. the print outside the spawner are executed first and then the spawner is spawned.
![Understanding how it works]( understanding.png "Understanding how it works")

## Multiple Spawn and removing drop
because the spawner isn't dropped, the executor will keep running. because executor will wait until there are no spawner. the added spawner runs concurently and asyncly so it runs together.
![Multiple Spawn and removing drop]( multiple-timer.png "Multiple Spawn and removing drop")