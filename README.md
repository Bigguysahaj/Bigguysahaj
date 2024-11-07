```ts
type Engineer = {
    writesCode: true
    hasCoffee: boolean
    currentlyBuilding: string[]
};

class Sahaj implements Engineer {

    private static instance: Sahaj  // singleton pattern becauase ✨unique
    public readonly age = 23

    public readonly location: 'Remote' | 'New Delhi' | 'Anywhere with good WiFi' = 
    "New Delhi" as const

    public readonly hasCoffee: boolean = !isChaiAvailable satisfies boolean

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
