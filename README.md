# intersection-

public void paintComponent(Graphics g){
super.paintComponent(g);
Graphics g2=(Graphics)g;
Shape s1 = new Ellipse2D.Double(0,0,100,100);
Shape s1 = new Ellipse2D.Double(60,0,100,100);
Area a1= new Area(s1);
Area a2= new Area(s2);
a1.add(a2);
g2.fill(a1);


         Shape s1 = new Ellipse2D.Double(60,0,100,100);
        Shape s2 = new Ellipse2D.Double(0,0,100,100);
        Area a1= new Area(s1);
         Area a2= new Area(s2);
         a1.intersect(a2);
         g2.fill(a1);

