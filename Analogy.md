教育

> 教育就像一副眼镜。
> 戴上眼镜之前和之后，我们看到的其实是同样的世界；但戴上眼镜之后，我们就能看得更清楚。
> 教育也一样，受教育之前与之后，我们身处的其实是同样的世界；可受教育之后，我们就能看得更清楚，想得更明白，选择得更有效，行动起来更有收获。

科学
> 科学确实是由信息构成的，正如房子是用砖头盖的一样。可问题在于，正如仅仅一堆砖头放在那儿我们不能称其为房子一样，一堆信息放在一块儿就叫科学，有点不像话。

#### Recursion
> Suppose you are sitting in an auditorium, and you'd like to know which row you are in. Let's assume the rows are not labelled. You could count all of the rows in front of you, but that would take quite a while. This is analogous to the iterative approach (using a loop). You are doing a lot of work. However, you realize there is a way to delegate that work to other people. You ask the person in front of you what row he is in. When he responds, you can simply add 1 to that row number. That person does the same thing. He asks the person in front of him, and that person asks the person in front of him, and so on. Each time a person is asked represents a function call. You are the first function call, the man in front of you is the next. However, none of the function calls are finished executing yet, since they are still waiting for responses. When finally the man in the front row is asked what row he is in, we have reached our base case. There is nobody ahead of him, so he knows that he is in row 1. He responds that he is in row 1. The person behind him knows he/she is in row 2, and this information bubbles back up to you, with each person in the chain adding 1 to the response they receive. This bubbling-up is analogous to the base case being reached, and then each recursive call resolving itself one by one, with the most recently called functions ending first. Finally, the man in front of you tells you his row number, you add 1, and you've found your answer. Each function call did very little work, and you still achieved a correct answer.

