# Exec

it is possible to create a custom file descriptor similar to 0, 1, and 2
`exec 3> file`
file will then be open to writing as 3.
`echo hi >&3` will write to file
