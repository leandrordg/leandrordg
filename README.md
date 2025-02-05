```ts
import { Developer } from "leandrordg";

interface AboutMe extends Developer {
  name: string;
  field: string;
  job: string;
  location: string;
}

interface Skills extends Developer {
  languages: string[];
  libraries: string[];
  frameworks: string[];
}

const aboutMe: AboutMe = {
  name: "Leandro Rodrigues",
  field: "Full Stack Web Developer",
  job: "Freelancer",
  location: "São Paulo, Brazil",
};

const skills: Skills = {
  languages: ["Javascript", "Typescript", "Python"],
  libraries: ["React", "React Native", "Node.js"],
  frameworks: ["Next.js", "Express.js"],
};

export { aboutMe, skills };
```
