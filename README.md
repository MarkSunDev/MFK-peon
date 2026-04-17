# Sanguosha Hero Voice Pack 🗡️

A sound pack inspired by the classic card game Sanguosha (Three Kingdoms Kill), bringing hero battle voices to your AI coding sessions.

## Event Mapping

| CESP Event | Sound |
|---|---|
| `session.start` | Hero entrance lines |
| `task.acknowledge` | Skill activation / card play |
| `task.complete` | Victory shout / elimination |
| `task.error` | Defeat / hero last words |
| `input.required` | Judgment phase / awaiting decision |
| `resource.limit` | Near-death gasp / no cards left |
| `session.end` | Farewell lines |
| `task.progress` | Battlefield ambience |
| `user.spam` | "Steady!" / "Patience!" |

## Adding Sounds

Drop `.mp3`, `.wav`, or `.ogg` files into the matching folder under `sounds/`, then update the `file` path in `openpeon.json`. Keep clips under 1 MB and 1–5 seconds long.

## License

CC-BY-NC-4.0. Original Sanguosha audio is copyrighted by Yoka Games — personal use only.
