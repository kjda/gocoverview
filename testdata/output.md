# gocoverview


<details> <summary> example.com/example/example.go </summary>

```
  1: package example
  2:
O 3: func example() bool {
O 4: 	println("covered")
X 5: 	if false {
X 6: 		println("not covered")
X 7: 	}
O 8: 	return true
  9: }

```

</details>
