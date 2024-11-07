```ts
interface Engineer { writesCode: true; hasCoffee: boolean; currentlyBuilding: string[] }

class Sahaj implements Engineer {

    private static instance: Sahaj  // singleton pattern becauase ✨unique
    public readonly location: 'Remote' | 'New Delhi' | 'Anywhere with good WiFi' = "New Delhi"
    public readonly hasCoffee: boolean = !isChaiAvailable satisfies boolean
    public readonly writesCode = true
    public readonly age = 23
    public currentlyBuilding = ['Campus', 'Aube', 'Fastest Real Estate Website', 'Cool Game']


    get hobbies () : string[] {
       return ["Jazz 🎷", "Chess ♟️", "Bouldering 🧗‍♂️", "Building Cool Stuff 👨‍💻"]
    }

     get languages(): Record<"Proficient" | "Familiar", string[]> {
        return {
            "Proficient": ["JavaScript", "TypeScript", "Python", "C++"],
            "Familiar": ["Java", "Golang", "Rust", "Lua", "Swift", "Flutter"]
        }
    }

    get email () : string[] {
        return ["sahaj.working@gmail.com"]
    }

}
```
