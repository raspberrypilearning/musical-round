## Concurrency

Now let's get two instruments working together to play the tune.

+ We don't want the second version to wait until the first has finished so we'll need to tell Sonic Pi that it doesn't need to wait. We do this by running each version inside a 'thread'.
    
    ![لقطة الشاشة](images/round-thread.png)
    
    In computing we call things happening at the same time 'concurrency'.

+ Run your code and see if you can hear two instruments.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/frerejacques2.mp3" type="audio/mpeg"> Your browser does not support the <code>audio</code> element. </audio>
    </div>
+ Look at the output and you will see the same notes being played by both instruments at the same time:
    
    ![لقطة الشاشة](images/round-conc-output.png)
    
    Each time is highlighted in a different colour.

+ Let's look at the music for this piece.
    
    Here are the first four bars:
    
    ![لقطة الشاشة](images/round-music1.png)
    
    And the final four bars:
    
    ![لقطة الشاشة](images/round-music2.png)
    
    Run your Sonic Pi project again and follow along.

+ Frere Jacques is a musical round. It's designed to sound good when multiple versions of it start at different times. You might have been involved in singing or playing a round in music lessons at school.
    
    Let's add a sleep before the piano starts playing:
    
    ![لقطة الشاشة](images/round-sleep.png)
    
    How does it sound?
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/frerejacques3.mp3" type="audio/mpeg"> Your browser does not support the <code>audio</code> element. </audio>
    </div>
+ Look at the output from Sonic Pi, can you see when the piano starts playing? And when the first instrument stops playing?
    
    ![لقطة الشاشة](images/round-conc-output2.png)
    
    This is just an excerpt, look at your Sonic Pi output to see the whole piece.