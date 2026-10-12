`nikita_potapov.py`

```python
from dataclasses import dataclass


@dataclass(frozen=True)
class Developer:
    name: str = "Nikita Potapov"
    role: str = "Full-Stack / Backend Developer"
    focus: tuple[str, ...] = (
        "Web applications and APIs",
        "DevOps and infrastructure",
        "AI integrations and automation",
    )

    tech_stack = {
        "languages": ["Python", "TypeScript", "JavaScript", "C++", "SQL", "Dart"],
        "backend": ["Django", "DRF", "FastAPI", "Pydantic"],
        "frontend": ["React", "Next.js", "HTML", "CSS"],
        "databases": ["PostgreSQL", "SQLite", "SQLAlchemy"],
        "devops": ["Docker", "Docker Compose", "Nginx", "GitHub Actions", "Linux"],
        "ai_and_automation": ["LLM integrations", "AI tools", "Telegram bots"],
        "other": ["Flutter", "Qt", "CMake", "STM32", "FreeRTOS"],
    }

    currently_building = (
        "Full-stack platforms with Python, React and Next.js",
        "Backend services and third-party integrations",
        "CI/CD pipelines and containerized deployments",
        "AI-powered applications and developer tools",
    )


projects = {
    "GoodFoodCoach": {
        "url": "https://goodfoodcoach.ru",
        "description": "Nutrition platform with courses, programs, community and admin tools",
        "stack": ["Next.js", "Django", "PostgreSQL", "Docker"],
    },
    "AnytoolAI Platform": {
        "url": "https://github.com/gushinets/anytoolai-platform",
        "description": "Collaborative development of AI platform features and tooling",
    },
    "VPN Management Bot": {
        "url": "https://github.com/NikitaPotapovIt/vpn_bot",
        "description": "VPN management, billing and administration via Telegram",
    },
    "Embedded RPC Framework": {
        "url": "https://github.com/NikitaPotapovIt/embedded-rpc-protocol",
        "description": "C++ RPC over UART for STM32 and FreeRTOS",
    },
    "Desktop Analytics": {
        "url": "https://github.com/NikitaPotapovIt/CPP3DW",
        "description": "Cross-platform data analysis with C++ and Qt",
    },
    "SmartCalc": {
        "url": "https://github.com/NikitaPotapovIt/CPP3_SmartCalc_v2.0",
        "description": "Desktop engineering and financial calculator in C++ and Qt",
    },
    "Link Shortener": {
        "url": "https://github.com/NikitaPotapovIt/link_shortener",
        "description": "URL shortening application with FastAPI",
    },
}

# Some current projects are maintained in private repositories.

contact = {
    "telegram": "https://t.me/nikitayurievichp",
    "linkedin": "https://www.linkedin.com/in/nikita-potapov-98a100346",
    "email": "nikitapotapovit@gmail.com",
}
```

`README.md` · [Live project: GoodFoodCoach](https://goodfoodcoach.ru) · [Telegram](https://t.me/nikitayurievichp) · [LinkedIn](https://www.linkedin.com/in/nikita-potapov-98a100346)
