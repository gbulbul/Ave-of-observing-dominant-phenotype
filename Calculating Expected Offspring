class expected_offspring:
    def find_expected_offspring(d_pairs_to_prob,k_val):
        ave_cal=0
        k_times_p_k=[k*p_k for k,p_k in zip(k_val,d_pairs_to_prob.values())]
        #print(k_times_p_k)
        for i in k_times_p_k:
            ave_cal+=2*i 
        return ave_cal
    
if __name__=="__main__":
    d_pairs_to_prob={}

    d_pairs_to_prob['AA-AA']=1
    d_pairs_to_prob['AA-Aa']=1
    d_pairs_to_prob['AA-aa']=1
    d_pairs_to_prob['Aa-Aa']=0.75
    d_pairs_to_prob['Aa-aa']=0.5
    d_pairs_to_prob['aa-aa']=0

    k_val=[1, 0, 0, 1, 0, 1]
    print(expected_offspring.find_expected_offspring(d_pairs_to_prob,k_val))
