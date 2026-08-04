// intento de audio (??) 


setcpm(25) 
  let drum = stack

  
    ( s("bd").beat("3,5,9,13",16), 
      s("st [bd mt]").beat("0,1,4,6,8,10,12,14",16), 
      s("cp").beat("4,12",16), 
      s("hh").beat("0,2,3,7,9,10,15",16), 
      s("lt").beat("2,4,6,8",16),
      s("sd").beat("4,6",16).slow(2),
    ).bank("RolandTr909")

let bass = stack


  ( s("sd oh").beat("3,5,9",16), 
    s("sd").beat("4,8,6,2",16),
  ).bank("RhythmAce")
  

let chords = 

  note("c2 c2 c2 c2").sound("casio").slow(4).gain(0.57)

let melodies = 

  note("2 1 [4 2] 3*2").sound("jazz")

$melodies: melodies 

$drum: drum 

$bass: bass 

$chords: chords
