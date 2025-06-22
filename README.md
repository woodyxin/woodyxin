## Hi there 👋

<!--
**woodyxin/woodyxin** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!--
import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Input } from "@/components/ui/input";
import { Badge } from "@/components/ui/badge";

const icons = [
  { name: "Java", src: "/icons/java.svg" },
  { name: "Spring", src: "/icons/spring.svg" },
  { name: "Docker", src: "/icons/docker.svg" },
  { name: "Linux", src: "/icons/linux.svg" },
];

export default function SkillIconsGallery() {
  const [query, setQuery] = React.useState("");
  const filteredIcons = icons.filter(icon => icon.name.toLowerCase().includes(query.toLowerCase()));

  return (
    <div className="p-6 space-y-6">
      <h1 className="text-3xl font-bold">My Custom Skill Icons</h1>
      <Input
        type="text"
        placeholder="Search skills..."
        value={query}
        onChange={e => setQuery(e.target.value)}
        className="max-w-md"
      />
      <div className="grid grid-cols-2 md:grid-cols-4 gap-4">
        {filteredIcons.map((icon, idx) => (
          <Card key={idx} className="flex flex-col items-center justify-center p-4">
            <img src={icon.src} alt={icon.name} className="w-16 h-16" />
            <CardContent className="text-center mt-2">
              <Badge variant="secondary">{icon.name}</Badge>
            </CardContent>
          </Card>
        ))}
      </div>
    </div>
  );
}

-->
