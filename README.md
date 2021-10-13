# Interface-Animal
This is a demo of an interface and it's references


Public interface Animal {
public void animalSound();
public void sleep ();
}
class Pig implements Animal {

public void animalSound() {
System.out.println("The pig says: wee wee");
}
public void sleep () {
System.out.println("Zzz");

Public class Main {
public static void main (String [] args) {
Pig myPig = new Pig();
myPig.animalsound();
myPig.sleep();
