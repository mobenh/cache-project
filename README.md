
# Golang Cache
In this project I used Golang to build a cache that has the most recent items only.
![image](https://user-images.githubusercontent.com/96225596/169418790-cf62a377-efd5-476b-9fb3-4964ea4cad50.png)

## Technologies Used
* Golang

## Dependencies

* Install Go - https://go.dev/doc/install

## Executing program
* Download the repository to your computer and go to project file
```
git clone https://github.com/mobenh/cache-project
cd cache-project
```
* Edit line 7 for the size of the queue
* Edit line 103 for the items in the queue
```
const SIZE = 5
for _, word := range []string{"parrot", "avocado", "dragonfruit", "tree", "potato", "tomato", "tree", "dog"} {
```
* Run code
```
go run main.go
```
