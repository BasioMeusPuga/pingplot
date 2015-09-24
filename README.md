# pingplot
Plot ping response times with gnuplot - in realtime

Tired of the ping tool giving you boring numbers that your brain refuses to comprehend out of sheer boredom? Devoid of the challenge of adding more bugs to your workflow that only more bash scripts can bring? Wait no more, intrepid adventurer!

Presenting, pingplot. Using cutting edge gnuplot technology, you can now display (in realtime) when your network started foaming at the mouth before it all went so horribly, horribly wrong.
*(Requires bc, gnuplot)*

Usage: 
 
    pingplot -a <address> -i <interval> -d (delete temporary files on exit) -x (Don't plot on exit)
    p / t to plot, q to quit

