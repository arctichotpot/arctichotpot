```javascript
class About extends Me {

    constructor() {
        this.name = "liu lin"
        this.professional = "Front-end Development"
        this.skills = {
            language: ["JavaScript", "Golang"],
            framework: ["Vue", "React", "Koa", "Gin"]
        }
        this.hobby = "sleep,playing games and coding"

    }

    Introduction () {
        return {
            name: this.name,
            professional: this.professional,
            skills: this.skills,
            hobby: this.hobby
        }
    }

}
```
