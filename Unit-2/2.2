#include<stdio.h>
int main(){
	int n, bt[20],wt[20],tat[20],p[20],i,j,temp;
	float avg_wt=0, avg_tat=0;
	//Input no of processes 
	printf("Enter no of processes: ");
	scanf("%d",&n);
	//Input burst time for each process
	printf("Enter burst time for each processes : \n");
	for(i=0;i<n;i++){
		printf("P%d : ",i+1);
		scanf("%d",&bt[i]);
		p[i]=i+1;//Stores the process id like p[0]=1
	}
	//Sort process acc to burst time
	for (i=0;i<n;i++){
		for (j=i+1;j<n;j++){
			if (bt[i]>bt[j]){
				//Swapping of burst times
				temp=bt[i];
				bt[i]=bt[j];
				bt[j]=temp;
				//Swapping of process id's
				temp=p[i];
				p[i]=p[j];
				p[j]=temp;
			}
		}
	}
	wt[0]=0;
	//Calculate waiting time for each process
	for (i=1;i<n;i++){
		wt[i]=wt[i-1]+bt[i-1];
	}
	//Calculate turnaround time each process 
	for (i=1;i<n;i++){
		tat[i]=wt[i]+bt[i];
		avg_wt+=wt[i];
		avg_tat+=tat[i];
	}
	printf("\nProcess\tBT\tWT\tTAT\n");
	for(i=0;i<n;i++){
		printf("P%d\t%d\t%d\t%d\n",p[i],bt[i],wt[i],tat[i]);
	}
	//Display averages
	printf("\nAverages Waiting time = %.2f",avg_wt/n);
	printf("\nAverages Turnarounnd time = %.2f",avg_tat/n);
	return 0;
}
