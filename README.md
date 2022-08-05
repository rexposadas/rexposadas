### Hi there 👋

```go
me := struct {
		Name, From, LivesIn string
		FavoriteLanguages   []string
		MiscFavorites       map[string][]string
	}{
		Name:    "Rex Posadas",
		From:    "USA",
		LivesIn: "Philippines",

		FavoriteLanguages: []string{"Go", "Elixir"},

		MiscFavorites: map[string][]string{
			"food":       {"Korean", "Filipino"},
			"past_times": {"reading", "sitting in coffee shops"},
			"sports":     {"golf", "biking", "bjj"},
		},
	}

```

Credit where credit is due, this idea come from [@BretFisher's](https://github.com/BretFisher) README.
