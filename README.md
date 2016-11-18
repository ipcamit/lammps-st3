#Snippets for quick LAMMPS input file

Put these files in you _User_ folder in ST3 for file highlighting and auto-completion of lammps input files. _User_ folder can be accesed by going to menu: _Prefernces > Browse Packages_. Usually the bottom-most folder will be _User_.

All files with extension *.in or *.lammps should show syntax highlighting now.

Currently there are 4 kinds of snippets: 

1. For initialization (atom type, periodic boundary etc). It contains all settings most commonly used by _me_ you can edit it as per your wish. To use it write **init** followed by <kbd>Tab</kbd> to complete it.
2. For input coeff styles defination like angle_style etc. type **styles** followed by <kbd>Tab</kbd> to complete it. now use <kbd>Tab</kbd> to cycle through all the fields you want to edit or fill.
3. Input/Output Data Files: Triggered by **data** + <kbd>Tab</kbd>. It will define an input read data file, which you shall edit. Followed by trajectory file vor viewing in VMD (lammpstrj) then binary restart file, thermo output for log file and timestep in the end. Use <kbd>Tab</kbd> to cycle through all relevent fields
4. Fixes: Currently only NVT and NPT are there, might add more later. To invoke type **nvt** or **npt** followed by <kbd>Tab</kbd>. As above, use <kbd>Tab</kbd> to cycle through all relevent editable fields.

So essentially now just few strokes: **init** + <kbd>Tab</kbd>, **styles** + <kbd>Tab</kbd>, **data** + <kbd>Tab</kbd>, **npt** or **nvt** + <kbd>Tab</kbd> should be able to give you a basic lammps input file.

As it should be obvious if anything goes wrong with your simulations or computers or anything else, you are only responsible for that.
