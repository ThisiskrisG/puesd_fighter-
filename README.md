# Puesd Fighter

Launch date: 2026-07-05

Puesd Fighter is a compact top-down action demo built with Godot 4. It's designed for quick pick-up-and-play sessions on mobile (Android) and showcases responsive melee combat and simple but effective enemy AI.

What it can do
- Chase and navigate: Enemies use NavigationAgent2D for dynamic pathfinding and obstacle avoidance to pursue the player.
- Melee combat: Enemies perform melee attacks with configurable range, damage, and cooldown.
- Smooth movement & animation: Uses CharacterBody2D and AnimatedSprite2D to provide run/idle animations with sprite flipping.
- Hit & death handling: Enemies can take damage and are freed from the scene when health reaches zero.
- Tunable difficulty: Speed, attack_range, attack_damage, and attack_cooldown are exposed as export variables for balancing.

Developer notes
- Player requirements: the player node should be added to the "player" group and expose a `take_damage(int)` method.
- Godot version: Project intended for Godot 4.x (NavigationAgent2D, CharacterBody2D, AnimatedSprite2D).

Files added
- `launch_calendar.csv` — 30-day post-launch schedule and tasks (import into your calendar or spreadsheet). Replace placeholders (e.g., [PLAY_STORE_LINK], [SUPPORT_EMAIL]) with real values.

How to run
1. Install Godot 4.x.
2. Open this folder as a project in the Godot editor.
3. Run the main scene (e.g., res://scenes/Main.tscn).

Support
Report bugs and feedback to: support@yourdomain.com

License
This project is released under the MIT License. See LICENSE for details.
