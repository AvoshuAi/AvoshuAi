from typing import List, Dict, Tuple


class jiaweing:
    """
    software engineer · designer · founder
    creating unique and original digital experiences
    """

    def __init__(self):
        self.name      = "Jia Wei Ng"
        self.alias     = "Jay"
        self.age       = 26
        self.location  = "Singapore"
        self.website   = "https://jiaweing.com"
        self.education = "BSc Computing Science · SIT + University of Glasgow"
        self.stack     = ["TypeScript", "Rust", "Python", ".NET", "Next.js", "Tauri", "React Native", "Postgres", "SQLite"]

    @property
    def bio(self) -> str:
        return (
            "just an ordinary guy building software.\n"
            "a designer and software engineer crafting unique, and original digital experiences.\n"
            "drawn to psychology, space, quantum mechanics, and the strange phenomena that shape the universe."
        )

    @property
    def achievements(self) -> List[str]:
        return [
            "Google APAC Solution Challenge 2025 — Top 10",
            "Dell InnovateFest 2025 — Finalist",
            "Dell Cloud Native Awards — 1st Place (x2)",
            "built titan.tf at 15 — 460k+ players, 20k+ Steam members",
            "founded 18 startups, shipped 17 apps",
            "top 25% Unsplash contributor — 460k+ views, 4.3k+ downloads",
            "87+ blog posts published",
        ]

    @property
    def setup(self) -> Dict[str, object]:
        return {
            "workstation": {
                "processor": "i7-14700KF",
                "gpu"      : "RTX 4070 Ti SUPER",
                "ram"      : "32GB DDR5",
            },
            "laptop"     : "MacBook Air M2 Midnight",
            "peripherals": [
                "Yunzii AL75 Keyboard",
                "AULA F75 Pro",
                "Shure SM7B + Focusrite Scarlett 2i2",
                "Fujifilm X-T50 + Sigma 18-50mm f2.8",
            ],
        }

    @property
    def contact(self) -> Tuple[str, str, str, str, str]:
        github   = "github.com/jiaweing"
        linkedin = "linkedin.com/in/jiaweing"
        twitter  = "x.com/jiaweihq"
        youtube  = "youtube.com/@jiaweihq"
        email    = "hey@jiaweing.com"

        return github, linkedin, twitter, youtube, email


jay = jiaweing()
