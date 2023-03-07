class GfG{
    //Function to reverse the queue.
    public Queue<Integer> rev(Queue<Integer> q){
        //add code here.
        Stack<Integer>st=new Stack<>();
        Queue<Integer>rev=new LinkedList<>();
        for(int i:q)
        {
            st.add(i);//4 3 1 10 2 6
        }
        while(!st.isEmpty())
        {
            rev.add(st.pop());
        }
        return rev;//6 2 10 1 3 4
    }
}
