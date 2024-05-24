```ts
class Sahaj {

    constructor() {  this.age = 22   this.pronouns = ['he', 'him']   this.locality = "New Delhi"  }

    get hobbies(): string[] {
        return ["Jazz" , "Reading", "Chess" , "Bouldering" , "Building Cool Stuff"]
    }

    get languages(): { [category: string]: { [level: string]: string[] } } {
        return {
            "Spoken": {
                "Fluent": [ "English", "Hindi", "French" ],
                "Learning": [ "Finnish", "Vietnamese", "Garhwali", "Dutch" ]
            },

            "Programming": {
                "Proficient": [ "JavaScript", "TypeScript", "Python", "C++" ],
                "Familiar": [ "Java", "Golang", "Rust", "Lua" , "Swift", "Flutter" ]
            }
        }
    }

    get contact(): { [method: string]: string[] } {
        return {
            "Email": ["sahaj.working@gmail.com"],
            "LinkedIn": ["https://www.linkedin.com/in/sahaj-singh-3a841b239/"]
        }

    }

}

```
