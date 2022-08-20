01. Variables musí mít vždy využití
02. Nemůžeme importovat variable, které nepoužíváme
03. Formated Output %v
04. Můžeme declare variable bez value, je ale nutné definovat zároneň type
05. Maps nezustavaji ve stejnem poradi v jakem jsme je vytvorili
06. Soubory pro test musi koncit na _test.go
07. Format specifiers - define the type of data to be printed on standard output.
08. The identifier can be for a variable, a constant, or a function.
09. Any identifier that starts with a capital is exported or visible from outside the package
10. Variadic parameter, which is the triple dots, can accept any number of arguments


```` bash
# když už máme cmd a pkg folders 
go run ./cmd/web

# spustíme všechny soubory najednou
go run . 

# ukáže nám enviroment
go env

# ukáže nám cestu k aplikaci
go env GOPATH

# unset GOPATH 
unset GOPATH

# vytvoříme mode file
go mod init myapp
 
# vytvoření variable a printing memory address, kam směřuje pointer pointer 
pes := "Amigo"
fmt.Println(&pes) 

# zformátuje (zlepší) vše co je v tomto folder
go fmt ./...

git clone git@github.com:ivanmafl/learning-go.git

````