    #include <stdio.h>

    int main() {
        int swiss, blue, lem, ice, match;
        int choice, pay, paynt;
        int totalL, totalI, totalM, totalS, totalB;
        int cnts, cntb, cntl, cnti, cntm, sums, sumb, suml, sumi, summ, sum;
        int quans, quanb, quanl, quani, quanm, total, change;

        sum = 0;
        cnts = 0;
        cntb = 0;
        cntl = 0;
        cnti = 0;
        cntm = 0;//for initialization para dili mushow si receipt if no orders
        totalS = 0;
        totalB = 0;
        totalL = 0;
        totalI = 0;
        totalM = 0;// di magka gubot ang overall output sa receipt
        quans = 0;
        quanb = 0;
        quanl = 0;
        quani = 0;
        quanm = 0;//di mushow ang ubang items sa menu bisan way orders

        printf("                  Welcome to Sweet Chat Cafe!\n\n");
        printf("-----------------  Please Select your Order: ------------------\n");

        do {
            printf("\n                            MENU:\n");
            printf("        1. Swiss Roll - P45.00\n");
            printf("        2. Blueberry Muffin - P50.00\n");
            printf("        3. Lemon Croissants - P60.00\n");
            printf("        4. Iced Hazelnut Mocha - P65.00\n");
            printf("        5. Matcha Frappe - P65.00\n");
            printf("        6. End Order\n\n");
            printf("Enter your choice (1-6): ");
            scanf("%d", &choice);
            if (choice < 0){
                break;
            }

    switch(choice){
    case 1:
    printf("Enter Quantity: ");
    scanf("%d", &quans);
    if (quans == 0){
    printf("Invalid choice. Please try again.\n");
    }else{
    swiss = 45;
    sum = quans * swiss + sum;
    cnts = cnts + 1;
    printf("Added %d Swiss Roll to your order. Your total is now P%d.00\n", quans, sum);
    totalS = totalS + quans;
    }
        break;
    case 2:
    printf("Enter Quantity: ");
    scanf("%d", &quanb);
    if (quanb == 0){
    printf("Invalid choice. Please try again.\n");
    }else{
    blue = 50;
    sum = quanb * blue + sum;
    cntb = cntb + 1;
    printf("Added %d Blueberry Muffin to your order. Your total is now P%d.00\n", quanb, sum);
    totalB = totalB + quanb;
    }
        break;
    case 3:
    printf("Enter Quantity: ");
    scanf("%d", &quanl);
    if (quanl == 0){
    printf("Invalid choice. Please try again.\n");
    }else{
    lem = 60;
    sum = quanl * lem + sum;
    cntl = cntl + 1;
    printf("Added %d Lemon Croissants to your order. Your total is now P%d.00\n", quanl, sum);
    totalL = totalL + quanl;
    }
        break;
    case 4:
    printf("Enter Quantity: ");
    scanf("%d", &quani);
    if (quani == 0){
    printf("Invalid choice. Please try again.\n");
    }else{
    ice = 65;
    sum = quani * ice + sum;
    cnti = cnti + 1;
    printf("Added %d Iced Hazelnut Mocha to your order. Your total is now P%d.00\n", quani, sum);
    totalI = totalI + quani;
    }
        break;
    case 5:
    printf("Enter Quantity: ");
    scanf("%d", &quanm);
    if (quanm == 0){
    printf("Invalid choice. Please try again.\n");
    }else{
    match = 65;
    sum = quanm * match + sum;
    cntm = cntm + 1;
    printf("Added %d Matcha Frappe to your order. Your total is now P%d.00\n", quanm, sum);
    totalM = totalM + quanm;
    }
        break;
    case 6:
     printf("End Order");
     break;

    default:
        printf("Invalid choice. Please try again.");
    }

  } while (choice != 6);

        if (cnts == 0 && cntb == 0 && cntl == 0 && cnti == 0 && cntm == 0) {
                printf("\nNo Order Has Been Made.\n");
        } else {

            printf("\n\nThank you for your order!\n");
            printf("Here is your order summary:\n");
            printf("-------------------------------------------------\n");
            sums = swiss * totalS;
            sumb = blue * totalB;
            suml = lem * totalL;
            sumi = ice * totalI;
            summ = match * totalM;
            printf("| Item                   | Quantity  | Price    |\n");
            printf("-------------------------------------------------\n");

            if (cnts != 0) {
                if (totalS > 9) {
                        if (totalS > 9 && sums > 999) {
                            printf("| Swiss Roll             | %d        | P%d.00 |\n", totalS, sums);
                        } else {
                            if (sums > 99) {
                        printf("| Swiss Roll             | %d        | P%d.00  |\n", totalS, sums);
                        } else {
                        printf("| Swiss Roll             | %d        | P%d.00   |\n", totalS, sums);
                    }
                        }
                        } else {
                            if (sums > 99) {
                        printf("| Swiss Roll             | %d         | P%d.00  |\n", totalS, sums);
                        } else {
                        printf("| Swiss Roll             | %d         | P%d.00   |\n", totalS, sums);
                    }
                }
            }

            if (cntb != 0) {
                if (totalB > 9) {
                        if (totalB > 9 && sumb > 999) {
                            printf("| Blueberry Muffin       | %d        | P%d.00 |\n", totalB, sumb);
                        } else {
                            if (sumb > 99) {
                        printf("| Blueberry Muffin       | %d        | P%d.00  |\n", totalB, sumb);
                    } else {
                        printf("| Blueberry Muffin       | %d        | P%d.00   |\n", totalB, sumb);
                    }
                        }
                        } else {
                            if (sumb > 99) {
                        printf("| Blueberry Muffin       | %d         | P%d.00  |\n", totalB, sumb);
                    } else {
                        printf("| Blueberry Muffin       | %d         | P%d.00   |\n", totalB, sumb);
                    }
                }
            }

            if (cntl != 0) {
                if (totalL > 9) {
                        if (totalL > 9 && suml > 999) {
                            printf("| Lemon Croissants       | %d        | P%d.00 |\n", totalL, suml);
                    } else {
                        if (suml > 99) {
                        printf("| Lemon Croissants       | %d        | P%d.00  |\n", totalL, suml);
                    } else {
                        printf("| Lemon Croissants       | %d        | P%d.00   |\n", totalL, suml);
                    }
               }
                    } else {
                        if (suml > 99) {
                        printf("| Lemon Croissants       | %d         | P%d.00  |\n", totalL, suml);
                    } else {
                        printf("| Lemon Croissants       | %d         | P%d.00   |\n", totalL, suml);
                    }
                }
            }

            if (cnti != 0) {
                if (totalI > 9) {
                        if (totalI > 9 && sumi > 999) {
                            printf("| Iced Hazelnut Mocha    | %d        | P%d.00 |\n", totalI, sumi);
                    } else {
                        if (sumi > 99) {
                        printf("| Iced Hazelnut Mocha    | %d        | P%d.00  |\n", totalI, sumi);
                    } else {
                        printf("| Iced Hazelnut Mocha    | %d        | P%d.00   |\n", totalI, sumi);
                    }
                }
                    } else {
                        if (sumi > 99) {
                        printf("| Iced Hazelnut Mocha    | %d         | P%d.00  |\n", totalI, sumi);
                    } else {
                        printf("| Iced Hazelnut Mocha    | %d         | P%d.00   |\n", totalI, sumi);
                    }
                }
            }

            if (cntm != 0) {
                if (totalM > 9) {
                        if (totalM > 9 && summ > 999) {
                            printf("| Matcha Frappe          | %d        | P%d.00 |\n", totalM, summ);
                    } else {
                        if (summ > 99) {
                        printf("| Matcha Frappe          | %d        | P%d.00  |\n", totalM, summ);
                    } else {
                        printf("| Matcha Frappe          | %d        | P%d.00   |\n", totalM, summ);
                    }
                }
                    } else {
                        if (summ > 99) {
                        printf("| Matcha Frappe          | %d         | P%d.00  |\n", totalM, summ);
                    } else {
                        printf("| Matcha Frappe          | %d         | P%d.00   |\n", totalM, summ);
                    }
                }
            }

            printf("-------------------------------------------------\n");

            total = sums + sumb + suml + sumi + summ;

          if (total > 999) {
                printf("| Total Cost             |           | P%d.00 |\n", total);
        } else {
            if (total > 99) {
                printf("| Total Cost             |           | P%d.00  |\n", total);
        } else {
                printf("| Total Cost             |           | P%d.00   |\n", total);
    }
}
            printf("-------------------------------------------------\n");
            do{

            printf("\nEnter payment amount: P");
            scanf("%d", &pay);

            if (total > pay) {
                printf("\nInsufficient payment. Payment amount is less than the total cost.\n");
                do {
                printf("Would you like to change the amount of payment? If so press 1, press 2 if otherwise: ");
                scanf("%d", &paynt);
                if (paynt > 2 || paynt == 0) {
                    printf("\nError Please Choose Again!\n");
                }
            }   while (paynt > 2 || paynt == 0);
                } else {
                paynt = 1;
                change = pay - total;
                printf("Payment successful. Change: P%d.00\n", change);
            }
        } while (pay < total && paynt == 1 || paynt > 2 || paynt == 0);
         printf("\n                 PLEASE COME AGAIN!\n");
    }

        return 0;
    }

