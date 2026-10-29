# MATH1052 Practice Questions: Units 1, 2, and 3.1

This document contains practice questions covering Unit 1, Unit 2, and Unit 3.1.

Use these questions to test understanding, review key ideas, and prepare for problem-solving.

Important: these are revision questions only. Try them without looking at worked solutions first.

---

## Unit 1: Ordinary Differential Equations

### Section 1.1: Introduction to ODEs

1. State whether each of the following is an ODE and give its order:
   - y' = 3x + 2
   - y'' + 4y' + 5y = 0
   - y' = xy
   - y' y = 1

2. Explain what it means for a function y(x) to be a solution of an ODE.

3. Show that y(x) = Ce^{x^2/2} is a solution of y' = xy.

4. Find the general solution of:
   - y' = x^2
   - y'' = 6x

5. Solve the initial value problem:
   - y' = 2x, y(0) = 3

6. A particle moves with constant velocity 60 km/h along a straight road. Write an ODE for its position and solve it.

### Section 1.2: Slope Fields and Equilibrium Solutions

7. What is a slope field? Explain how it is used to understand a differential equation.

8. Find the equilibrium solutions of:
   - y' = y(1 - y)
   - y' = 2t + 1
   - y' = sin(4y)

9. Explain the difference between a stable and an unstable equilibrium.

10. For the ODE y' = y^2, identify the equilibrium solution and describe its stability.

11. Explain why two solution curves to the same ODE cannot cross.

### Section 1.3: Euler’s Method

12. Explain in words how Euler’s method uses tangent lines to approximate a solution curve.

13. Use Euler’s method with step size h = 0.2 to approximate y(0.6) for:
   - y' = 2t, y(0) = 0

14. Why does Euler’s method become more accurate when the step size is reduced?

15. For the IVP y' = sin(xy), y(0) = 1, explain how you would set up Euler’s method numerically.

### Section 1.4: Separable ODEs

16. State what it means for a first-order ODE to be separable.

17. Solve:
   - dy/dx = x/y
   - dy/dx = y(1 - y)
   - dy/dx = x e^y

18. Solve the IVP:
   - dy/dx = x/y, y(0) = 3

19. Solve:
   - dy/dx = sin y / x, y(1) = 1

20. Explain why singular solutions must be checked when solving separable ODEs.

21. Find the equilibrium solutions of the logistic equation:
   - dy/dt = y(1 - y)

### Section 1.5: Applications: Cooling and Population Growth

22. State Newton’s law of cooling and write the corresponding ODE.

23. Solve the cooling model:
   - dT/dt = -k(T - T_m), T(0) = T_0

24. A population follows exponential growth with ODE dP/dt = rP. Solve this equation.

25. Explain why the exponential model may be unrealistic for large populations.

26. Write down the logistic population model and explain the role of the carrying capacity.

27. Find the equilibrium solutions of:
   - dP/dt = rP(1 - P/\theta)

28. Explain what happens to the population if P is much smaller than the carrying capacity, and if P is close to the carrying capacity.

### Section 1.6: Linear First-Order ODEs

29. State the standard form of a first-order linear ODE.

30. Solve:
   - y' + 2y = e^x
   - y' + (1/x)y = x

31. Explain how an integrating factor is used to solve a linear ODE.

32. Solve the IVP:
   - x^2 y' + xy = 1, y(1) = 2

33. For the RL circuit model, explain why the equation is linear and how the integrating factor is chosen.

### Section 1.7: Second-Order Linear ODEs with Constant Coefficients

34. State the general form of a homogeneous linear second-order ODE with constant coefficients.

35. Solve:
   - y'' + 5y' + 6y = 0
   - y'' - 9y = 0

36. Solve the IVP:
   - y'' - 4y = 0, y(0) = 1, y'(0) = 2

37. Explain the meaning of the characteristic equation.

38. For the equation y'' + 9y = 0, find the general solution.

39. Describe the three cases that arise when solving a constant-coefficient second-order ODE.

### Section 1.8: Harmonic Motion and Damped Oscillations

40. Write the equation for undamped simple harmonic motion.

41. Explain the meaning of the spring constant and angular frequency.

42. Write the equation for a damped spring system.

43. Describe the difference between underdamped, critically damped, and overdamped motion.

44. Why does damping reduce the amplitude of oscillation?

45. A mass-spring system is modelled by x'' + 2x' + 5x = 0. What type of damping is present?

46. Describe the motion of a critically damped spring in words.

---

## Unit 2: Functions of Several Variables

### 2.1 Visualising Functions of Several Variables

47. What is a function of two variables? Give an example.

48. Explain why the graph of z = f(x, y) is a surface in 3D.

49. What is a level curve? Give an example.

50. What is a cross-section? Give an example.

51. For z = x^2 + y^2, describe the level curves and the shape of the graph.

52. For z = x^2 - y^2, describe the shape and explain why it is called a saddle surface.

53. For z = x + y, describe the surface and its level curves.

54. Why are level curves useful for visualising a surface?

### 2.2 Conic Sections

55. Name the four main conic sections.

56. Write the standard form of a circle and explain how to identify its centre and radius.

57. Write the standard form of an ellipse and explain what a and b represent.

58. Write the standard form of a parabola and identify the vertex.

59. Write the standard form of a hyperbola and explain what the asymptotes tell you.

60. Convert x^2 + y^2 - 6x + 4y - 12 = 0 to standard form and identify the conic.

61. Complete the square for y = x^2 - 8x + 20 and identify the vertex.

62. Identify the conic section represented by:
   - x^2 + y^2 = 25
   - x^2/9 + y^2/4 = 1
   - y = x^2 - 5
   - x^2/4 - y^2/9 = 1

63. Explain how you can tell the difference between an ellipse and a hyperbola from the equation.

64. What does the general quadratic equation Ax^2 + Bxy + Cy^2 + Dx + Ey + F = 0 represent?

65. Why is completing the square an important method in conic sections?

### 2.3 Partial Derivatives

66. Define the partial derivative ∂f/∂x.

67. Define the partial derivative ∂f/∂y.

68. For f(x,y) = x^2 + y^2, find f_x and f_y.

69. For f(x,y) = x^3 y^2, find f_x and f_y.

70. For f(x,y) = sin(xy), find f_x and f_y.

71. For f(x,y) = e^{x^2 y}, find f_x and f_y.

72. Geometrically, what does ∂f/∂x represent?

73. Why do we treat the other variable as a constant when differentiating partially?

74. Find f_x and f_y for f(x,y) = x^2 + 3xy + y^2.

### 2.4 Higher-Order Partial Derivatives

75. Define f_xx, f_yy, f_xy, and f_yx.

76. For f(x,y) = x^2 + y^2, find all second-order partial derivatives.

77. For f(x,y) = x^2 y^3, find f_xy and f_yx.

78. Explain why mixed partial derivatives are often equal.

79. What do second partial derivatives tell you about a surface?

80. Why are second derivatives important in optimisation?

### 2.5 Chain Rule for Several Variables

81. If z = f(x,y), x = x(t), y = y(t), state the chain rule formula for dz/dt.

82. Let z = x^2 + y^2, x = t, y = 2t. Find dz/dt.

83. Let z = xy, x = cos t, y = sin t. Find dz/dt.

84. Let z = x^2 y, x = t^2, y = t^3. Find dz/dt.

85. State the general formula for ∂z/∂u when z = f(x,y), x = x(u,v), y = y(u,v).

86. Explain why the multivariable chain rule contains both partial derivatives and ordinary derivatives.

### 2.6 Gradient and Directional Derivative

87. Define the gradient vector ∇f.

88. For f(x,y) = x^2 + y^2, find the gradient.

89. Explain why the gradient points in the direction of greatest increase.

90. What is a directional derivative?

91. State the formula D_u f = ∇f · u.

92. Show that the gradient is perpendicular to a level curve.

93. For f(x,y) = x^2 + y^2 at (1,2), find the gradient and explain its meaning.

94. If u is a unit vector, explain how D_u f measures the rate of change of f in that direction.

### 2.7 Tangent Planes

95. State the formula for the tangent plane to z = f(x,y) at (a,b).

96. Find the tangent plane to z = x^2 + y^2 at (1,2).

97. Find the tangent plane to z = x + y at (2,3).

98. For z = xy at (1,2), find the tangent plane.

99. Explain why partial derivatives are used in the tangent plane formula.

100. What does the tangent plane represent geometrically?

### 2.8 Local Maxima, Minima, and Saddle Points

101. Define a critical point.

102. Solve for the critical point(s) of f(x,y) = x^2 + y^2.

103. Classify the critical point of f(x,y) = x^2 - y^2.

104. For f(x,y) = -x^2 - y^2, find and classify the critical point.

105. State the second derivative test.

106. For f(x,y) = x^2 + 2y^2, find the type of critical point.

107. Explain why a saddle point is neither a local max nor a local min.

108. What is the geometric meaning of a critical point?

---

## Unit 3.1: Limits and Continuity

109. Define the limit lim_(x,y)→(a,b) f(x,y).

110. Why are multivariable limits more complicated than single-variable limits?

111. Explain why the same function may approach different values along different paths.

112. Show that the limit lim_(x,y)→(0,0) xy/(x^2 + y^2) does not exist.

113. Show that the limit lim_(x,y)→(0,0) x^2 y / (x^4 + y^2) does not exist.

114. Evaluate the limit lim_(x,y)→(1,2) (x^2 + y^2).

115. Determine whether the limit lim_(x,y)→(0,0) x^2 y / (x^2 + y^2) exists.

116. Explain why testing only the x-axis and y-axis paths is not enough.

117. Define continuity for a function of two variables at a point (a,b).

118. Show that f(x,y) = x^2 + y^2 is continuous everywhere.

119. Explain why the function 1/(x^2 + y^2) is not continuous at (0,0).

120. If a function is continuous at a point, what can you conclude about the limit there?

121. State the rule: if two different paths give different limiting values, what does that tell you?

122. Explain the difference between a limit existing and a function being continuous.

123. In your own words, explain why the limit must be the same along every path in the domain if it exists.

124. Suppose a function is defined on a restricted domain D. Why must we only consider paths that remain in D when evaluating the limit?

125. Explain how polar coordinates can help analyse a multivariable limit.

126. Using polar coordinates, explain why xy/(x^2 + y^2) does not have a limit at (0,0).

127. Using the squeeze theorem, show that x^2 y / (x^2 + y^2) → 0 as (x,y) → (0,0).

128. Explain why finding the same value on two paths is not enough to prove the limit exists.

129. Give an example where the limit fails because different paths give different values.

130. Give an example where the limit exists because the function is continuous.

---

## Mixed Challenge Questions (Higher Difficulty)

131. For each equation below, identify the type of conic and explain your reasoning:
   - x^2 + y^2 = 16
   - x^2/9 + y^2/4 = 1
   - y = x^2 - 5
   - x^2/4 - y^2/9 = 1

132. Solve and classify the critical points of:
   - f(x,y) = x^2 + y^2 - 4x - 6y + 10

133. Find the tangent plane to z = x^2 + y^2 at (1,2) and interpret the result geometrically.

134. Decide whether the limit exists:
   - lim_(x,y)→(0,0) (x^2 y)/(x^4 + y^2)

135. Determine whether the function f(x,y) = (x^2 - y^2)/(x^2 + y^2) has a limit at (0,0).

136. Solve the initial value problem:
   - y' = y(1-y), y(0)=1/2

137. Find the general solution of:
   - y'' + 4y' + 4y = 0

138. Use Euler’s method with h = 0.1 to estimate y(0.3) for:
   - y' = x + y, y(0) = 1

139. Explain the difference between a level curve and a cross-section of a surface.

140. A function of two variables is continuous at a point. What does that imply about the limit and the function value there?

---

## Final Review Questions

141. Explain the relationship between conic sections, level curves, and surfaces.

142. Why is differentiability in multivariable calculus tied to continuity and local linear approximation?

143. Describe how the gradient and tangent plane are connected.

144. Explain how the path test is used to prove a multivariable limit does not exist.

145. Summarise the main ideas of Unit 1, Unit 2, and Unit 3.1 in a few sentences each.

146. Explain why the same function can behave very differently in 1D and 2D limits.

147. Write a short paragraph explaining the most important “big idea” from Unit 1 and the most important “big idea” from Unit 2.

148. If asked to solve a multivariable limit, what is the first thing you should check?

149. If a function is polynomial, what does that tell you about continuity and limits?

150. If a limit is shown to fail along two different paths, what conclusion can you draw immediately?

---

## Quick Diagnostic Checklist

Before moving on, make sure you can answer the following:

- Do I know how to identify a conic section from its equation?
- Can I complete the square correctly?
- Can I compute partial derivatives correctly?
- Can I explain what the gradient means?
- Do I know how to test whether a multivariable limit exists?
- Can I explain why continuity is connected to limits?
- Do I know the difference between a stable and unstable equilibrium?
- Can I solve a separable ODE and a first-order linear ODE?
- Can I solve a constant-coefficient second-order ODE?

---

This set of questions is designed to cover the key concepts, challenge your reasoning, and help you prepare for assessment-style tasks.
