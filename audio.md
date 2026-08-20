// another one
setcpm(25) 



let drum = stack( 

  s("bd").beat("3,5,9,13",16), 
  s("st [bd mt]").beat("0,1,4,6,8,10,12,14",16), 
  s("cp").beat("4,12",16), 
  s("hh").beat("0,2,3,7,9,10,15",16), 
  s("lt").beat("2,4,6,8",16),
  s("sd").beat("4,6",16).slow(2),
).bank("RolandTr909")




let bass = stack( 

  s("sd oh").beat("3,5,9",16), 
  s("sd hh").beat("4,8,6,2",16),
).bank("RhythmAce")

let melodies = stack(
  s("crow <hh oh>")
)






$drum: drum
$melodies: melodies
$bass: bass
