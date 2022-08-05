### Hi there 👋

```go
type Me struct {
	Name           string
	From, LivesIn  string
	FavoriteThings map[string][]string
}

func main() {
	me := Me{
		Name:    "Rex Posadas",
		From:    "USA",
		LivesIn: "Philippines",
	}

	favorites := map[string][]string{
		"food":       {"Korean", "Filipino"},
		"past_times": {"reading", "sitting coffee shops"},
	}

	me.FavoriteThings = favorites

	log.Printf("%+v", me)
}

```
