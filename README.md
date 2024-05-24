```ts
class Sahaj {

    constructor() {
        this.age = 22
        this.locality = "New Delhi"
    }

    get hobbies () : string[] {
        return ["Jazz" , "Chess" , "Bouldering" , "Building Cool Stuff"]
    }

    get languages () : { [category : string] : { [level : string] : string[] } } {
        return {
            "Spoken": {
                "Fluent" : ["English", "Hindi", "French"],
                "Learning" : ["Finnish", "Vietnamese", "Garhwali", "Dutch"]
            },
    
            "Programming" : {
                "Proficient": ["JavaScript", "TypeScript", "Python", "C++"],
                "Familiar": ["Java", "Golang", "Rust", "Lua", "Swift", "Flutter"]
            }
        }
    }

    get email () : string[] {
        return ["sahaj.working@gmail.com"]
    }

}
```
