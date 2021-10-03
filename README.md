# Go - Get Started

## What is Go 
- Go was developed by Robert Griesemer, Rob Pike, and Ken Thompson at Google in 2007
- Go is an open source programming language
- Go is a cross-platform. It works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc.)
- Go can be used to create high-performance applications
- Go supports concurrency
- Go is a fast, statically typed, compiled language that feels like a dynamically typed, interpreted language
- Go's syntax is similar to C++ but significant different points are
	- Go does not support classes and objects
	- Go does not support inheritance
	- Go has automatic garbage collection
	- Go is fast compile time

## What is Go Used For?
- Web development (server-side)
- Developing network-based programs
- Developing cross-platform enterprise applications
- Cloud-native development

## Go Install
Get a relevant installation files at https://golang.org/dl/.
</br>Follow the instructions related to your operating system. </br>
To verify if Go was installed successfully, run this command in terminial
```sh
go version
```
![goVersioin](https://user-images.githubusercontent.com/73010204/135742492-8ef5c0ed-7cb2-4ac2-9261-01651b3200ad.PNG)</br>
What is the version you get?

## IDE - config VS Code to use Go
- Launch the VS Code editor
- Open the extension manager(Ctrl + Shift + x), type "go" and hit enter
- Find the Go extension by the GO team at Google and install the extension</br>
![configureGo](https://user-images.githubusercontent.com/73010204/135742278-8c8abec2-91d9-4f0e-b0b3-296b2f539222.PNG)
- After that, open the command palette( Ctrl + Shift + p), run the Go: Install/Update Tools command
- Select all the provided tools and click OK to install all.</br>
![configureGo2](https://user-images.githubusercontent.com/73010204/135742282-963c311a-8286-4ac7-a960-5c1501a52474.PNG)

## Run the code
In the folder that includes your Go source files (such as helloworld.go file)
In the ternimal (cmd or VS code terminial), type and run
```sh
go mod init example.com/hello
go run .\helloworld.go
```
![outHelloWorld](https://user-images.githubusercontent.com/73010204/135742322-ed7c686f-66da-4604-96fe-3490e99d2d5c.png)

**Congratulations!** You have successfully created your first Go program.
To save the program as an executable, type and run:
```sh
go build .\helloworld.go
```
and you will get helloworld.exe
