# Nutrition Science | Childhood Obesity Nutrition Guide

English version translated from the existing Chinese README.

An AI popular-science conversation assistant based on the **Dietary and Nutrition Guide for Children and Adolescents with Obesity (2024 Edition)** issued by the **General Office of the National Health Commission**. | Nutrition Science Skill

> 🌱 I am new to AI and hope to use AI to share nutrition knowledge and help more people. If anything is insufficient, feedback is welcome. I will keep working on more nutrition-science skills. If you find this useful, please consider giving it a ⭐ Star. Thank you!

---

## Guideline Source

- **Full title**: *Dietary and Nutrition Guide for Children and Adolescents with Obesity (2024 Edition)*
- **Issuing organization**: General Office of the National Health Commission

## Features

- **Childhood obesity assessment**: BMI percentile plus waist circumference, distinguishing overweight and obesity levels
- **Dietary-nutrition principles**: 6 official principles for targeted childhood weight-management guidance
- **Traditional Chinese medicine dietary support**: 5 syndrome patterns (stomach heat with fire constraint / internal phlegm-dampness / qi stagnation and blood stasis / spleen deficiency with impaired transportation / spleen-kidney yang deficiency) plus dietary formulas
- **Regional meal plans**: 5 regions × 24 days of sample menus adapted to children’s eating habits
- **Safety boundaries**: clearly states that children should not blindly diet; growth and weight management must both be considered
- **Physical activity and screen time**: combines physical-activity guidance with sedentary-behavior reduction
- **Popular-science style**: plain language, concrete quantities, and myth correction—precise without being condescending

## Quick Reference

| Item | Recommendation | Plain-language explanation |
|------|----------------|----------------------------|
| Overweight criterion | BMI ≥ the 85th percentile for the same age and sex | Overweight; attention is needed |
| Obesity criterion | BMI ≥ the 95th percentile for the same age and sex | Intervention is needed |
| Screen time (ages 2–5) | ≤1 hour/day | Less phone time, more movement |
| Screen time (ages 6–17) | ≤2 hours/day | Move during study breaks too |
| Exercise (school-age children) | ≥60 min/day of moderate-to-vigorous activity | PE plus recess activity can help |
| Sugar-sweetened beverages | Avoid or drink less | One bottle of cola is roughly the calories of half a bowl of rice |
| Weight-loss pace | 0.5–1 kg/month for overweight/obesity | Do not rush; children are still growing |

## Knowledge System

| KPK ID | Topic | Source section |
|--------|-------|----------------|
| KPK-01~06 | Six major dietary-nutrition principles | Dietary-nutrition principles chapter |
| KPK-07~12 | Appendix knowledge: food choices, menus, nutrition formulas, etc. | Appendices 1–6 |
| KPK-13~14 | Disease background and TCM understanding | Preface + disease characteristics |

## Scope

- Primary users: primary healthcare workers (including nutrition guidance staff), parents of children and adolescents aged 2–17, and school doctors
- Use cases: prevention, control, and daily dietary-nutrition guidance for simple childhood/adolescent obesity where diet and nutrition are the main focus
- Note: secondary obesity caused by endocrine, genetic, neurologic, or other diseases should be diagnosed medically first

## File Structure

```text
- skill.yaml: Skill configuration, including guideline source, creator information, and disclaimer
- system_prompt.md: System prompt for the popular-science conversation style
- knowledge_base.md: KPK knowledge base with 14 knowledge points
- recipes_data.md: 5 regions × 24 days of sample menus
- dietary_formulas.md: 10 nutrition formulas
- README.md: Chinese README
- install.sh: Linux/macOS install script
- install.bat: Windows install script
```

## Statement

**Disclaimer**:
1. All content comes from the guideline above and is for dietary-nutrition popular-science reference only; it does not replace medication treatment or professional medical diagnosis.
2. Children and adolescents are growing and developing; blind dieting or extreme weight loss is not recommended.
3. Medication or surgical treatment is not recommended for children and adolescents with simple obesity.
4. If major comorbidities such as kidney dysfunction or heart failure are present, seek medical evaluation first.
5. Food-medicine substances should be used under professional guidance and not taken in excessive amounts.
6. This skill was built with AI assistance. Although it aims to stay faithful to the original guideline, paraphrasing errors may exist. If there is any doubt, please refer to the official published guideline text.


## Creator

**Runyuan Wang**
- Chinese Registered Dietitian
- M.S. in Nutrition and Food Hygiene, Kunming Medical University
- Built with WorkBuddy

## License

MIT
