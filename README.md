The issue seems to be with blank routes. Please see [this line](https://github.com/jpmckearin/ng5-rxjs-issue/blob/d2074f62a2c2810d3f65f10aafa8b879354568bc/src/app/app-routing.module.ts#L10) to toggle the issue on/off. To recreate the issue, make sure the aforementioned line is commented out, run `ng serve`, click on the `About` navigation link at the top of the page.
