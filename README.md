```shell
$ git clone https://github.com/Genbuchan/Genbuchan.git
$ cd Genbuchan
$ ./introduction
```

```
Hello everyone! I am Genbuchan<Ryo Shigematsu>. Thank you to find me!

First of all, please let me introduce myself using JSON-LD.
```

```json
{
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Ryo Shigematsu",
    "alternateName": "Genbuchan",
    "birthDate": "2001-04-10",
    "url": "https://genbuchan.com/",
    "email": "contact@genbuchan.com",
    "hasOccupation": [
        {
            "@type": "Role",
            "hasOccupation": {
                "@type": "Occupation",
                "name": "Web Engineer",
                "description": "I worked as a STOP COVID-19 KYOTO with Kyoto Prefectural Government.",
                "url": "https://github.com/stop-covid19-kyoto/covid19-kyoto/"
            },
            "startDate": "2020",
            "endDate": "2022"
        },
        {
            "@type": "Role",
            "hasOccupation": {
                "@type": "Occupation",
                "name": "Swift Engineer",
                "description": "I worked as a Swift enginner at startup company."
            },
            "startDate": "2022",
            "endDate": "2023"
        }
    ]
}
```

```
I glad to meet you!
```
