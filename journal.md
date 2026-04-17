## Daniel Herrera
## Linear Algebra Journey
## 4-14-2026
Episode 1: The Geometry of Linear Eq.

I had watched this episode a while ago. Everything had made intuitive sense but this time around something had really clicked.
It was considering the idea of if you can solve Ax=b for every b.
It makes very good sense, after taking algebra 1, that it is easy to see this for 2x2 systems.
It is taught that lines could have 1 solution, where they intersect at 1 point.
Or they could intersect at all of their points if they were the same.
And if they were parallel, they would never intersect.
He also mentioned the idea of independence, invertability, and non-singularity.
This made sense after he said that a column doesn't depend on another.
If we go back to the 2-d picture, I guess the lines being the same makes them dependent on each other.
I know I am reading far to deep into this one but I know it will be important later, and it is cool to see it already forming so early.

Episode 2: Elimination with Matrices

Before I speak about the lesson, I have to express a terrible discovery I had found at around 30 minutes in the lecture.
I didn't know originally that order mattered when multiplying a matrix. It turns out multiplying on the left side of the matrix gives row operations, while multiplying on the right give column operations.
I must rewrite somethings, and I hope that will be the last time I make that mistake. Should be.

I have watched about 2 more minutes and he exemplified that point. It turns out that the rest of my notes kept that true, so it wasnt so much of a problem.

The next thing that is beginning to break my heart is how difficult the practice sets seem, although after closer inspection they really aren't too bad.
Also they include answers, which makes it not fun to solve. Hopefully, I will be able to just learn through the videos. I don't need the indepth explanation too soon, after all the goal is to just make programs demonstrating these concepts that I am learning.
Also I don't have MatLab and probably won't until I reach college. I really am handing out excuses but I should try at least some of them.

I found that you could write row operations as matrices very cool, rather than writing out stuff like R_2 - 2 * R_1. Other than that pretty simple stuff. I've seen that triangular matrix many times which makes it familiar to me, like an old friend.

Episode 3: Multiplication and Inverse Matrices

I am lost. Will look this over then stop for today. Stopped at 21:24.
I'm guessing here that you do have quite a bit of background knowledge to understand all of this, and this is the part where I am a bit foggy. I had learned this in algebra 2, earlier this year and it was quite difficult. I believe I don't have the
intuitive understanding of this yet and maybe I will eventually but it is not here right now. I had just memorized important rules to solve questions. Now, it is time to get an intuitive sense of it.

## 4-15-2026

Episode 3: Multiplication and Inverse Matrices cont.

Just finished it past my bedtime because I ran out of time in the day to fit it in, but I really wanted to fit it in, it's all I've been thinking about.
Anyways we found out how to find the inverse of a matrix. The whole idea is centered around how the inverse of a matrix multiplied by the matrix would be equal to the identity matrix, or AA^-1=I.
This builds onto why some matrices are not invertible, because instead of I they could get 0, which defeats the whole purpose. If you can find a vector x where Ax=0, then the matrix is not invertible.
Then he explains Gauss-Jordan elimination by doing E[AI]=[IA^-1] and noticing that E[A]=I which means that E=A^-1. Those letters mean very little in text, but after the explanation you can see it unfold for your self.
It is a fun way to find the inverse by using intuition and elimination, rather than memorizing a formula, which I had done previously for Algebra 2.

I am very excited for the next day, I will have much less homework which means that I can have more time for this. Also with the help of ChatGPT, I was able to fully understand the multiple methods of matrix multiplication. I guess my brain had stopped working after working through those 3 lectures. I know that the rate at which I watch these lectures will slow down because I will now be entering new territory regarding the episodes that I havent watched at all. That is all for now.

## 4-16-2026

Episode 4: Factorization into A = LU

This episode included the introduction of lower triangular matrices. These come from the inverse of our elimination matrices, preformed in reverse order. It makes sense considering EA=U and A=E^-1U and A=LU which means that L = E^-1U.
Quite simple and with no row exchanges E^-1 becomes L. But then he introduced the row exchanges, being permuations. This reminds me of solving my Rubiks Cube, that was a term they had used for it.
Then, we go into an interesting topic about the cost of all of this. It turns out that for n x n matrix, the amount of operations on A to get it to U would be (n^3)/3 but the cost for every b would be n^2. Crazy, will have to keep in mind when coding to be efficient. I also had attempted some random problems from the practice sets, some to some success, most to failure. But it is alright, after all I'm not actually taking the course and I am proud of my work. I might share it at the end if I feel some questions were rewarding to solve, and that I'm proud enough to show it.
