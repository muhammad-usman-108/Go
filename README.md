
# Golang

Go is an open source programming language that makes it easy to build simple, reliable, and efficient software.

#### Installing For Linux
1. Go to the offical site of [Golang](https://golang.org/).
2. Click on Download.
3. Download the installor for linux.
4. Download the archive and extract it into /usr/local, creating a Go directory in /usr/local/go using the command:
      ``` 
       tar -C /usr/local -xzf go1.14.1.linux-amd64.tar.gz
    ```
5. Add /usr/local/go/bin to the PATH environment variable. You can do this by adding this line to your /etc/profile (for a system-wide installation) or $HOME/.profile:
    ```
    export PATH=$PATH:/usr/local/go/bin
    ```
6. Now check the version of Go 
    ```
    go version
    ```


#### Test Your Installation !
To check that Go is installed correctly or not ? Build a simple program, as follows.

1. Create a file named hello.go
2. Put the following code in hello.go file
    ```
    package main
    
    import "fmt"
    
    func main() {
    	fmt.Printf("hello, world\n")
    }
    ```
3. Then build it with the go tool:
    ```
    go build hello.go
    ```
4. The command above will build an executable named hello in the current directory alongside your source code. 
5. Execute it to see the greeting:
    ```
    ./hello
    ```
6. If you see the "hello, world" message then your Go installation is working.

Before rushing off to write Go code please read the How to Write Go Code document, which describes some essential concepts about using the [Go tools](https://golang.org/doc/).

### Error ?
If you are facing the error 'Command go not found' then run the following commands:

    
    sudo apt install golang-go
    sudo apt install gccgo-go 
    
