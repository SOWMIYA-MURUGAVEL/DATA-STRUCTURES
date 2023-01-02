
import java.util.*;
class LinkedList {

    Node head;
   static class Node {
    int value;
    Node next;
    Node(int d) {
      value = d;
      next = null;
    }
  }
  public void insertAtBeg(int val){
      Node nn = new Node(val);
      if(head==null){
          head=nn;
      }else{
          nn.next=head;
          head=nn;
          
      }
  }
  public void insertAtEnd(int val){
      Node nn = new Node(val);
      if(head==null){
          head=nn;
      }else{
         Node temp = head;
          while(temp.next!=null){
              temp=temp.next;
          }
          temp.next=nn;
      }
  }
  public void display(){
      Node temp = head;
      while(temp!=null){
          System.out.print(temp.value+"->");
          temp=temp.next;
      }
      System.out.print("\n");
  }
  public void insertAtPos(int pos,int val){
      Node nn = new Node(val);
      Node temp=head;
      for(int i=0;i<pos;i++){
          temp=temp.next;
      }
      nn.next=temp.next;
      temp.next=nn;
  }
}
  
class Main{
  public static void main(String[] args) {

    // create an object of LinkedList
    LinkedList ll = new LinkedList();
    ll.insertAtBeg(10);
    ll.insertAtBeg(23);
    ll.insertAtBeg(5);
    ll.display();
    ll.insertAtEnd(20);
    ll.display();
    ll.insertAtPos(2,70);
    ll.display();
    }
  }
