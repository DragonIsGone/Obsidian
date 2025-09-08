#### pygame.sprite.collide_rect
- The default method
- makes a bounding box
- unity square collider
- rectangle
```
collision_list = pygame.sprite.spritecollide(player, collectable_group, False)
```

#### Pygame.sprite.collide_circle
- Round sprites collider
- .radius modifies the size

#### Do Kill
- Tell if needs to remove 
## FPS
#### Benefits
- Reduces CPU load
- Maintain consistancy in speeds
```

```
## Timer 
#### Max function
max has two arguments
1. Lowest possible value
2. current value
### saving list of top score
```
import shelve

with shelve.open('highscore') as db:
	top_scores = db.get('top_scores', [])

	top_scores.append(new_score)
	top_scores = sorted(top_scores, reversed=True)
	top_scores = top_scores[:3]

	#save
	db['top_socres'] = top_scores
```


#### shelve.open('highscore')
- initializes directory
- creates/access
#### With
- with is a context manager
- makes code cleaner and safer
##### Using with
```
with shelve.open('highscore') as db:
	db['score'] = 200
```
##### Without with
```
db = shelve.open('highscore')
db['score'] = 200
db.close() #have to close
```

#### Sort

| Code               | Result      | Use case                 |
| ------------------ | ----------- | ------------------------ |
| sorted(top_scores) | Low -> High | Default, simplest syntax |
| sorted(top_scores) |             |                          |

#### Read and dislpay
```
print("Top 3 Scores:)
for i, score in enumerate(top_scores)
	print(f"{i+1}. {score}")
```
#### Display on screen
```
y = 100
for i, score in enumerate(top_scores):
	score_text = font.render(f"{i+1}. {score}", True)
	screen.blit(score.text, (50, y)
	y += 40
```
### Colours

```
WHITE = (255, 255, 2555)
DARK_BLUE = (0, 100, 200)
```

### Button
```
button_rect = pygame.Rect(x, y, width, height)
# define

# text_rect = text
```

```
if event.type == pygame.MOUSEBUTTONDOWN
```
## Basic Pygame
```
running = True
while running:
    clock.tick(60)
    for event in pygame.event.get():
        if event.type == pygame.QUIT:
            running = False
```

