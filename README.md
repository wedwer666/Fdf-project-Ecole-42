# Fdf-project-Ecole-42

This project is about creating a simplified graphic “wireframe” (“fils de fer” in french,
hence the name of the project) representation of a relief landscape linking various points
(x, y, z) via segments. The coordinates of this landscape are stored in a file passed as
a parameter to your program. 

Each number corresponds to a point in space:
• The horizontal position corresponds to its axis.
• The vertical position corresponds to its ordinate.
• The value corresponds to its altitude.


The executable file must be named fdf.
• You must submit a Makefile.
• Your Makefile must compile the project and must contain the usual rules. It must
recompile and re-link the program only if necessary.
• If you are clever, you will use your library for your fdf. Submit also your folder
libft including its own Makefile at the root of your repository. Your Makefile
will have to compile the library, and then compile your project.
• You cannot use global variables.
• Your project must be written in accordance with the Norm.
• You have to handle errors carefully. In no way can your program quit in an unexpected
manner (Segmentation fault, bus error, double free, etc).
• You’ll have to submit a file called author containing your username followed by a
’\n’ at the root of your repository.
