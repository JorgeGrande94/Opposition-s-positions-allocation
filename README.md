# Opposition-s-positions-allocation
Little project to read the list of the positions available from a public job offer from one file, and the list of the opponents who passed the examen from another file. 
Based on the position (the grade they obtained in the examen) they opponents will pick their favourite position, and the program will update both files.

Please feel free to edit the script to add any improvement or to fix any of the errors the program has. I only ask you to add the proper comments so I can understand 
the changes, and of course open a new branch to edit the script.

Regarding the Excel files:

-Lista_opositores: 
  This file contains the list of the opponents who passed the examen. You can add more opponents if you want but keep in mind:
    -The two first rows must not be edited
    -The mandatory fields to add a new opponent are: 
      -Nombre: name
      -Apellidos: last name
      -Posición: the priority to choose position based on the grade obtained in the examen (if posición = 1 it means this opponent got the maximum note)
      -Edad: age
      -Ciudad_origen: home town
 You can add also the three fields of "Plaza deseada" (desired position -> city, hospital and specialty), or you can do it later running the program.
 The fields of "Plaza asignada" will be added by running the program.

-Plazas:
  This file contains the list of the available positions for the public job offer. You can add more positions if you want but keep in mind:
    -The first row must not be edited
    -The mandatory fields to add a new position are:
      -Ciudad: city
      -Hospital
      -Especialidad: specialty
      -Asignación: the position of the opponent to whom the position has been allocated. When you add a new position, it would be unallocated, and the default 
      value for "Asignación" in this case is 0. It will be updated by running the program.


