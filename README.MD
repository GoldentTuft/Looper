# looper

```elm
import Looper as Lp

updateDays : Int -> Date -> Date
updateDays amount date =
    { date | day = Lp.new date.day 1 31 |> Lp.add amount |> Lp.get }
```

1,2,...31,1,23


