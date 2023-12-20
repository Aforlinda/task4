# Instructions on how to Run and Test Your Application

## Functions
A number of functions were used in this code

They include 
* func main
* func indexHandler
* func uploadHandler
* func downloadHandler
* func deleteHandler
* func styleHandler
* func waitForShutdown

### func main 
To test the main function run 

```Golang
package main

import (
	"testing"
)
func Test_main(t *testing.T) {
	tests := []struct {
		name string
	}{
		
	}
	for _, tt := range tests {
		t.Run(tt.name, func(t *testing.T) {
			main()
		})
	}
}

```

### func indexHandler
To test this run 
```Golang
package main

import (
	"net/http"
	"testing"
)
func Test_indexHandler(t *testing.T) {
	type args struct {
		w http.ResponseWriter
		r *http.Request
	}
	tests := []struct {
		name string
		args args
	}{
		
	}
	for _, tt := range tests {
		t.Run(tt.name, func(t *testing.T) {
			indexHandler(tt.args.w, tt.args.r)
		})
	}
}

```


### func uploadHandler
To test this run
```Golang
package main

import (
	"net/http"
	"testing"
)
func Test_uploadHandler(t *testing.T) {
	type args struct {
		w http.ResponseWriter
		r *http.Request
	}
	tests := []struct {
		name string
		args args
	}{
		
	}
	for _, tt := range tests {
		t.Run(tt.name, func(t *testing.T) {
			uploadHandler(tt.args.w, tt.args.r)
		})
	}
}

```
### func downloadHandler
To test this run
```Golang
package main

import (
	"net/http"
	"testing"
)
func Test_downloadHandler(t *testing.T) {
	type args struct {
		w http.ResponseWriter
		r *http.Request
	}
	tests := []struct {
		name string
		args args
	}{
		
	}
	for _, tt := range tests {
		t.Run(tt.name, func(t *testing.T) {
			downloadHandler(tt.args.w, tt.args.r)
		})
	}
}

```
### func deleteHandler
To test this run
```Golang
package main

import (
	"net/http"
	"testing"
)
func Test_deleteHandler(t *testing.T) {
	type args struct {
		w http.ResponseWriter
		r *http.Request
	}
	tests := []struct {
		name string
		args args
	}{
		
	}
	for _, tt := range tests {
		t.Run(tt.name, func(t *testing.T) {
			deleteHandler(tt.args.w, tt.args.r)
		})
	}
}

```
### func styleHandler
To test this run
```Golang
package main

import (
	"net/http"
	"testing"
)
func Test_styleHandler(t *testing.T) {
	type args struct {
		w http.ResponseWriter
		r *http.Request
	}
	tests := []struct {
		name string
		args args
	}{
		
	}
	for _, tt := range tests {
		t.Run(tt.name, func(t *testing.T) {
			styleHandler(tt.args.w, tt.args.r)
		})
	}
}

```
### func waitForShutdown 
To test this run
```Golang
package main

import (
	"testing"
)
func Test_waitForShutdown(t *testing.T) {
	tests := []struct {
		name string
	}{
		
	}
	for _, tt := range tests {
		t.Run(tt.name, func(t *testing.T) {
			waitForShutdown()
		})
	}
}

```
