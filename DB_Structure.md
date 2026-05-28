## 1. Topic Metadata

Basic organizational info.
```json
{
  "id": "linear_equations_intro",
  "title": "Introduction to Linear Equations",
  "chapter": "Algebra",
  "difficulty": "beginner",
  "estimated_time": 25,
  "prerequisites": [
    "basic_arithmetic"
  ],
  "tags": [
    "equations",
    "variables",
    "algebra"
  ]
}
```
## 2. Concept Explanation

This is extremely important.

I think explanations should NOT just be plain paragraphs.

Instead structured intentionally.

Example:
```josn
{
  "concept_explanation": {
    "core_idea": "...",
    "intuition": "...",
    "visualization": "...",
    "real_world_analogy": "...",
    "common_misconception": "..."
  }
}
```
This is powerful because you force yourself to teach:

- formally
- intuitively
- visually
- psychologically

all separately.

That’s very important.

## 3. Key Examples

Examples should probably contain:

- question
- steps
- explanation per step
- reasoning

Example:
```json
{
  "examples": [
    {
      "question": "2x + 3 = 7",
      "steps": [
        {
          "expression": "2x = 4",
          "explanation": "Subtract 3 from both sides"
        },
        {
          "expression": "x = 2",
          "explanation": "Divide both sides by 2"
        }
      ],
      "final_answer": "x = 2"
    }
  ]
}
```
## 4. Understanding Check

This is different from exercises.

These are:

- conceptual checks
- intuition checks
- small confidence checks

Example:
```json
{
  "understanding_check": [
    {
      "type": "multiple_choice",
      "question": "Why do we subtract 3 from both sides?",
      "options": [
        "To isolate x",
        "To remove the variable",
        "To simplify randomly"
      ],
      "correct_answer": 0,
      "explanation": "Subtracting equally preserves balance."
    }
  ]
}
```
## 5. Exercise Levels

This is probably your most important structure.

Instead of:

- random question dump

you organize by:

- cognitive difficulty progression

Example:
```json
{
  "exercise_levels": [
    {
      "level": 1,
      "title": "Basic Isolation",
      "difficulty_note": "Single operation equations",
      "additional_explanation": "...",
      "hint_strategy": "...",
      "exercises": []
    }
  ]
}
```
Then each exercise:
```json
{
  "question": "x + 5 = 9",
  "answer": "x = 4",
  "hints": [
    "What is added to x?",
    "How can you undo addition?"
  ],
  "solution": {
    "steps": [
      {
        "expression": "x = 9 - 5",
        "explanation": "Subtract 5 from both sides"
      },
      {
        "expression": "x = 4",
        "explanation": "Simplify"
      }
    ]
  }
}
```
## 6. Difficulty Transitions

This is something most systems completely ignore.

But your idea naturally supports it.

Example:
```json
{
  "transition_note": {
    "from_level": 2,
    "to_level": 3,
    "new_challenge": "Equations now include brackets.",
    "mental_shift": "You must distribute multiplication before isolating x.",
    "mini_example": "3(x + 2) = 12"
  }
}
```
This is genuinely valuable.

Because learners often fail at:

- transitions

not concepts themselves.

## 7. Common Mistakes

This becomes extremely useful later.

Example:
```json
{
  "common_mistakes": [
    {
      "mistake": "Incorrect distribution",
      "example": "3(x + 2) = 3x + 2",
      "correction": "Multiplication applies to every term inside brackets."
    }
  ]
}
```
## 8. Reflection

Very underrated.

Example:
```json
{
  "reflection": [
    {
      "question": "What part felt hardest?"
    },
    {
      "question": "Could you solve without hints?"
    }
  ]
}
```
## 9. Adaptive Metadata

Future ready structure.

Example:
```json
{
  "analytics": {
    "mastery_weight": 0.8,
    "recommended_review_days": 3,
    "concept_dependencies": [
      "basic_arithmetic"
    ]
  }
}
```