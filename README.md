### Hi there 👋

```go
	me := struct {
		Name, From, LivesIn string
		Favorites           map[string][]string
		Sports              []string
	}{
		Name:    "Rex Posadas",
		From:    "USA",
		LivesIn: "Philippines",
		Favorites: map[string][]string{
			"food":       {"Korean", "Filipino"},
			"past_times": {"reading", "sitting in coffee shops"},
		},
		Sports: []string{"golf", "biking", "BJJ"},
	}

```
