# Hi! My name is Slava Kapski. 
![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Rubik&size=25&pause=1000&color=F7BA0C&random=false&width=435&lines=I'm+Front-end+Developer)

#### **My contacts** 
**Phone📱:** +375336623846

**Email 📧:** kapskij20@gmail.com

## About me:
My main goal is professional growth and development in the field of information technology. My strengths include hard work and perseverance in solving assigned tasks, the ability to get along with the team, as well as flexibility in various matters.

## Skills 🛠 
- JavaScrips 
- HTML
- CSS
- React
- TypeScript
- Git
- GitHub
- Figma
- Adobe Photoshop


## 🔗 Code Examples

```
type PropsType = ButtonProps & {
    name?: string
    callBack: () => void
    children?: ReactNode
}

export let SuperButton: React.FC<PropsType> = (props) => {
    const { name, callBack, variant, children, ...otherProps } = props
    return (
        <Button onClick={callBack}
            variant = {variant ? variant : 'contained'}
            size={'small'}
            {...otherProps}>
            {name}
        </Button>
    )
}
```

