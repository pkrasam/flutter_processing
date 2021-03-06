# Flutter Processing

A Flutter port of [Processing](https://processing.org/reference/).

This project is not affiliated with the Processing project or related organizations.

---

Do you get value from this package? Please consider supporting SuperDeclarative!

<a href="https://donate.superdeclarative.com" target="_blank" alt="Donate"><img src="https://img.shields.io/badge/Donate-%24%24-green"></a>

---

# Implemented Features

## Structure
- [ ] thread()
- [ ] setup()
- [ ] draw()
- [ ] redraw()
- [ ] setLocation()
- [ ] setResizable()
- [ ] setTitle()
- [ ] loop()
- [ ] noLoop()
- [ ] push()
- [ ] pushStyle()
- [ ] pop()
- [ ] popStyle()
- [ ] exit()

## Environment
- [ ] settings()
- [ ] width
- [ ] height
- [ ] size()
- [ ] pixelDensity()
- [ ] pixelHeight
- [ ] pixelWidth
- [ ] displayDensity()
- [ ] fullScreen()
- [ ] frameRate()
- [ ] frameRate
- [ ] frameCount
- [ ] cursor()
- [ ] noCursor()
- [ ] focused
- [ ] smooth()
- [ ] noSmooth()
- [ ] delay()

## Data
### Composite
- [ ] Array
- [ ] ArrayList
- [ ] FloatDict
- [ ] FloatList
- [ ] HashMap
- [ ] IntDict
- [ ] IntList
- [ ] JSONArray
- [ ] JSONObject
- [ ] Object
- [ ] String
- [ ] StringDict
- [ ] StringList
- [ ] Table
- [ ] TableRow
- [ ] XML

### Conversion
- [ ] binary()
- [ ] boolean()
- [ ] byte()
- [ ] char()
- [ ] float()
- [ ] hex()
- [ ] int()
- [ ] str()
- [ ] unbinary()
- [ ] unhex()

### String Functions
- [ ] join()
- [ ] match()
- [ ] matchAll()
- [ ] nf()
- [ ] nfc()
- [ ] nfp()
- [ ] nfs()
- [ ] split()
- [ ] splitTokens()
- [ ] trim()

### Array Functions
- [ ] append()
- [ ] arrayCopy()
- [ ] concat()
- [ ] expand()
- [ ] reverse()
- [ ] shorten()
- [ ] sort()
- [ ] splice()
- [ ] subset()

## Shape
- [ ] createShape()
- [ ] loadShape()
- [ ] PShape

### 2D Primitives
- [ ] arc()
- [ ] circle()
- [ ] ellipse()
- [ ] line()
- [ ] point()
- [ ] quad()
- [ ] rect()
- [ ] square()
- [ ] triangle()

### Curves
- [ ] bezier()
- [ ] bezierDetail()
- [ ] bezierPoint()
- [ ] bezierTangent()
- [ ] curve()
- [ ] curveDetail()
- [ ] curvePoint()
- [ ] curveTangent()
- [ ] curveTightness()

### 3D Primitives
- [ ] box()
- [ ] sphere()
- [ ] sphereDetail()

### Attributes
- [ ] ellipseMode()
- [ ] rectMode()
- [ ] strokeCap()
- [ ] strokeJoin()
- [ ] strokeWeight()

### Vertex
- [ ] beginContour()
- [ ] beginShape()
- [ ] bezierVertex()
- [ ] curveVertex()
- [ ] endContour()
- [ ] endShape()
- [ ] quadraticVertex()
- [ ] vertex()

### Loading & Displaying
- [ ] shape()
- [ ] shapeMode()

## Input
### Mouse
- [ ] mouseButton
- [ ] mouseClicked()
- [ ] mouseDragged()
- [ ] mouseMoved()
- [ ] mousePressed()
- [ ] mousePressed
- [ ] mouseReleased()
- [ ] mouseWheel()
- [ ] mouseX
- [ ] mouseY
- [ ] pmouseX
- [ ] pmouseY

### Keyboard
- [ ] key
- [ ] keyCode
- [ ] keyPressed()
- [ ] keyPressed
- [ ] keyReleased()
- [ ] keyTyped()

### Files
- [ ] BufferedReader
- [ ] createInput()
- [ ] createReader()
- [ ] launch()
- [ ] loadBytes()
- [ ] loadJSONArray()
- [ ] loadJSONObject()
- [ ] loadStrings()
- [ ] loadTable()
- [ ] loadXML()
- [ ] parseJSONArray()
- [ ] parseJSONObject()
- [ ] parseXML()
- [ ] selectFolder()
- [ ] selectInput()

### Time & Date
- [ ] day()
- [ ] hour()
- [ ] millis()
- [ ] minute()
- [ ] month()
- [ ] second()
- [ ] year()

## Output
### Text Area
- [ ] print()
- [ ] printArray()
- [ ] println()

### Image
- [ ] save()
- [ ] saveFrame()

### Files
- [ ] beginRaw()
- [ ] beginRecord()
- [ ] createOutput()
- [ ] createWriter()
- [ ] endRaw()
- [ ] endRecord()
- [ ] PrintWriter
- [ ] saveBytes()
- [ ] saveJSONArray()
- [ ] saveJSONObject()
- [ ] saveStream()
- [ ] saveStrings()
- [ ] saveTable()
- [ ] saveXML()
- [ ] selectOutput()

## Transform
- [ ] applyMatrix()
- [ ] popMatrix()
- [ ] printMatrix()
- [ ] pushMatrix()
- [ ] resetMatrix()
- [ ] rotate()
- [ ] rotateX()
- [ ] rotateY()
- [ ] rotateZ()
- [ ] scale()
- [ ] shearX()
- [ ] shearY()
- [ ] translate()

## Lights, Camera
### Lights
- [ ] ambientLight()
- [ ] directionalLight()
- [ ] lightFalloff()
- [ ] lights()
- [ ] lightSpecular()
- [ ] noLights()
- [ ] normal()
- [ ] pointLight()
- [ ] spotLight()

### Camera
- [ ] beginCamera()
- [ ] camera()
- [ ] endCamera()
- [ ] frustum()
- [ ] ortho()
- [ ] perspective()
- [ ] printCamera()
- [ ] printProjection()

### Coordinates
- [ ] modelX()
- [ ] modelY()
- [ ] modelZ()
- [ ] screenX()
- [ ] screenY()
- [ ] screenZ()

### Material Properties
- [ ] ambient()
- [ ] emissive()
- [ ] shininess()
- [ ] specular()

## Color
### Setting
- [ ] background()
- [ ] clear()
- [ ] colorMode()
- [ ] fill()
- [ ] noFill()
- [ ] noStroke()
- [ ] stroke()

### Creating & Reading
- [ ] alpha()
- [ ] blue()
- [ ] brightness()
- [ ] color()
- [ ] green()
- [ ] hue()
- [ ] lerpColor()
- [ ] red()
- [ ] saturation()

## Image
- [ ] createImage()
- [ ] PImage

### Loading & Displaying
- [ ] image()
- [ ] imageMode()
- [ ] loadImage()
- [ ] noTint()
- [ ] requestImage()
- [ ] tint()

### Textures
- [ ] texture()
- [ ] textureMode()
- [ ] textureWrap()

### Pixels
- [ ] blend()
- [ ] copy()
- [ ] filter()
- [ ] get()
- [ ] loadPixels()
- [ ] pixels[]
- [ ] set()
- [ ] updatePixels()

## Rendering
- [ ] blendMode()
- [ ] clip()
- [ ] createGraphics()
- [ ] hint()
- [ ] noClip()
- [ ] PGraphics

### Shaders
- [ ] loadShader()
- [ ] PShader
- [ ] resetShader()
- [ ] shader()

## Typography
- [ ] PFont

### Loading & Displaying
- [ ] createFont()
- [ ] loadFont()
- [ ] text()
- [ ] textFont()

### Attributes
- [ ] textAlign()
- [ ] textLeading()
- [ ] textMode()
- [ ] textSize()
- [ ] textWidth()

### Metrics
- [ ] textAscent()
- [ ] textDescent()

## Math
- [ ] PVector

### Calculation
- [ ] abs()
- [ ] ceil()
- [ ] constrain()
- [ ] dist()
- [ ] exp()
- [ ] floor()
- [ ] lerp()
- [ ] log()
- [ ] mag()
- [ ] map()
- [ ] max()
- [ ] min()
- [ ] norm()
- [ ] pow()
- [ ] round()
- [ ] sq()
- [ ] sqrt()

### Trigonometry
- [ ] acos()
- [ ] asin()
- [ ] atan()
- [ ] atan2()
- [ ] cos()
- [ ] degrees()
- [ ] radians()
- [ ] sin()
- [ ] tan()

### Random
- [ ] noise()
- [ ] noiseDetail()
- [ ] noiseSeed()
- [ ] random()
- [ ] randomGaussian()
- [ ] randomSeed()

## Constants
- [ ] HALF_PI
- [ ] PI
- [ ] QUARTER_PI
- [ ] TAU
- [ ] TWO_PI