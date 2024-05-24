```ts
class Sahaj {

    constructor() {
        this.age = 22
        this.locality = "New Delhi"
    }

    get hobbies () : string[] {
        return ["Jazz" , "Chess" , "Bouldering" , "Building Cool Stuff"]
    }

    get languages () : { [category : string] : { [level : string] : string[] } }
        "Spoken": {
            "Fluent" : ["English", "Hindi", "French"],
            "Learning" : ["Finnish", "Vietnamese", "Garhwali", "Dutch"]
        },
        "Programming" : {
            "Proficient" : ["JavaScript", "TypeScript"],
            "Familiar" : ["Python", "Java", "C++"]
        }
    }

    get email () : string[] {
        return ["sahaj.working@gmail.com"]
    }

}
```
