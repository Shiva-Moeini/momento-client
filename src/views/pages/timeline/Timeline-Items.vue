<script lang="ts" setup>

import { VDateInput } from 'vuetify/labs/VDateInput'


</script>

<template>
  <VRow>
    <VCol cols="12">
      <VCard title="Timeline-Items"><VCardText>
          
          <VForm class="mt-6">
            <VRow>
              <VCol
                md="6"
                cols="12"
              >
                <VTextField
                  placeholder="Applied for Job"
                  label="Event Title"
                />
              </VCol>
              <VCol
                cols="12"
                md="6"
              >
                <VTextField
                  label="Event Description"
                  placeholder="Submitted my application to XYZ company for a software engineer role."
                />
              </VCol>


              <VCol
                cols="12"
                md="6"
              >
              
              <v-date-input 
              label="Date input" 
              clearable variant="outlined" 
              prepend-icon="" 
              prepend-inner-icon='bx bx-calendar'
              >
              </v-date-input>
                
              </VCol>

              
              <VCol
                cols="12"
                md="6"
              >
                <v-file-input label="File input" variant="outlined" prepend-inner-icon ='bx bxs-camera'> </v-file-input>
              </VCol>

           
              <VCol
                cols="12"
                class="d-flex flex-wrap gap-4"
              >
                <VBtn>Save changes</VBtn>

                <VBtn
                  color="secondary"
                  variant="tonal"
                  type="reset"
                >
                  Reset
                </VBtn>
              </VCol>
            </VRow>
          </VForm>
        </VCardText>
      </VCard>
    </VCol>

  </VRow>
</template>
