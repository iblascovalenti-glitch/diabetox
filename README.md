/**
 * # Project Documentation
 *
 * ## Overview
 * This proyect aksjlfkjasbvkfjalksfbask
 *
 * ## Data Retrieval Process
 * - The application initiates a request to the specified API endpoint and savess iterating along the API response limits.
 * - Upon receiving the full dataset, it is all saved on a single json file.
 * - This data is then transformed using an LLM from a medical description of the patient to a csv file with the following columns we will use as features:
    -
    -
    -
    -


 * ## Decisions Taken
 * - the values for HbA1c and Random Glucose extracted from the medical notes will, when not explicitly expressed as "high/low/medium" values instead of numeric ones, be put in said brackets

 * - rg_ranges{"low": (0,70),
             "normal": (71,139),
             "high": (140,200),
             "elevated": (140,200),
             "very high": (200,math.inf),
            }
    hbca1c_ranges{"low: (0,4),
                "normal": (4.1,5.5),
                "high": (5.6,6.4),
                "elevated": (5.6,6.4),
                "very high": (6.5,7),
                }
                
 * -  The medical notes are from Natural Institution of Diabetes and Digestive and Kidney Diseases (NIDDK)
    American Diabetes Association (ADA)
    World Health Organization (Who)
 */
